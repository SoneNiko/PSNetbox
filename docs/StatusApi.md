# PSOpenAPITools.PSOpenAPITools\Api.StatusApi

All URIs are relative to *https://netbox.grid.uchicago.edu/api/schema*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Invoke-StatusRetrieve**](StatusApi.md#Invoke-StatusRetrieve) | **GET** /api/status/ | 


<a id="Invoke-StatusRetrieve"></a>
# **Invoke-StatusRetrieve**
> System.Collections.Hashtable Invoke-StatusRetrieve<br>



A lightweight read-only endpoint for conveying NetBox's current operational status.

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


try {
    $Result = Invoke-StatusRetrieve
} catch {
    Write-Host ("Exception occurred when calling Invoke-StatusRetrieve: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**System.Collections.Hashtable**](AnyType.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

