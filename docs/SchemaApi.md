# PSOpenAPITools.PSOpenAPITools\Api.SchemaApi

All URIs are relative to *https://netbox.grid.uchicago.edu/api/schema*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Invoke-SchemaRetrieve**](SchemaApi.md#Invoke-SchemaRetrieve) | **GET** /api/schema/ | 


<a id="Invoke-SchemaRetrieve"></a>
# **Invoke-SchemaRetrieve**
> System.Collections.Hashtable Invoke-SchemaRetrieve<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Format] <String><br>



OpenApi3 schema for this API. Format can be selected via content negotiation.  - YAML: application/vnd.oai.openapi - JSON: application/vnd.oai.openapi+json

### Example
```powershell
# general setting of the PowerShell module, e.g. base URL, authentication, etc
$Configuration = Get-Configuration
# Configure API key authorization: cookieAuth
$Configuration.ApiKey.sessionid = "YOUR_API_KEY"
# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
#$Configuration.ApiKeyPrefix.sessionid = "Bearer"

# Configure API key authorization: tokenAuth
$Configuration.ApiKey.Authorization = "YOUR_API_KEY"
# Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
#$Configuration.ApiKeyPrefix.Authorization = "Bearer"

$Format = "json" # String |  (optional)

try {
    $Result = Invoke-SchemaRetrieve -Format $Format
} catch {
    Write-Host ("Exception occurred when calling Invoke-SchemaRetrieve: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Format** | **String**|  | [optional] 

### Return type

[**System.Collections.Hashtable**](AnyType.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/vnd.oai.openapi, application/yaml, application/vnd.oai.openapi+json, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

