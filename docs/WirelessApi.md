# PSOpenAPITools.PSOpenAPITools\Api.WirelessApi

All URIs are relative to *https://netbox.grid.uchicago.edu/api/schema*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Invoke-WirelessWirelessLanGroupsBulkDestroy**](WirelessApi.md#Invoke-WirelessWirelessLanGroupsBulkDestroy) | **DELETE** /api/wireless/wireless-lan-groups/ | 
[**Invoke-WirelessWirelessLanGroupsBulkPartialUpdate**](WirelessApi.md#Invoke-WirelessWirelessLanGroupsBulkPartialUpdate) | **PATCH** /api/wireless/wireless-lan-groups/ | 
[**Invoke-WirelessWirelessLanGroupsBulkUpdate**](WirelessApi.md#Invoke-WirelessWirelessLanGroupsBulkUpdate) | **PUT** /api/wireless/wireless-lan-groups/ | 
[**Invoke-WirelessWirelessLanGroupsCreate**](WirelessApi.md#Invoke-WirelessWirelessLanGroupsCreate) | **POST** /api/wireless/wireless-lan-groups/ | 
[**Invoke-WirelessWirelessLanGroupsDestroy**](WirelessApi.md#Invoke-WirelessWirelessLanGroupsDestroy) | **DELETE** /api/wireless/wireless-lan-groups/{id}/ | 
[**Invoke-WirelessWirelessLanGroupsList**](WirelessApi.md#Invoke-WirelessWirelessLanGroupsList) | **GET** /api/wireless/wireless-lan-groups/ | 
[**Invoke-WirelessWirelessLanGroupsPartialUpdate**](WirelessApi.md#Invoke-WirelessWirelessLanGroupsPartialUpdate) | **PATCH** /api/wireless/wireless-lan-groups/{id}/ | 
[**Invoke-WirelessWirelessLanGroupsRetrieve**](WirelessApi.md#Invoke-WirelessWirelessLanGroupsRetrieve) | **GET** /api/wireless/wireless-lan-groups/{id}/ | 
[**Invoke-WirelessWirelessLanGroupsUpdate**](WirelessApi.md#Invoke-WirelessWirelessLanGroupsUpdate) | **PUT** /api/wireless/wireless-lan-groups/{id}/ | 
[**Invoke-WirelessWirelessLansBulkDestroy**](WirelessApi.md#Invoke-WirelessWirelessLansBulkDestroy) | **DELETE** /api/wireless/wireless-lans/ | 
[**Invoke-WirelessWirelessLansBulkPartialUpdate**](WirelessApi.md#Invoke-WirelessWirelessLansBulkPartialUpdate) | **PATCH** /api/wireless/wireless-lans/ | 
[**Invoke-WirelessWirelessLansBulkUpdate**](WirelessApi.md#Invoke-WirelessWirelessLansBulkUpdate) | **PUT** /api/wireless/wireless-lans/ | 
[**Invoke-WirelessWirelessLansCreate**](WirelessApi.md#Invoke-WirelessWirelessLansCreate) | **POST** /api/wireless/wireless-lans/ | 
[**Invoke-WirelessWirelessLansDestroy**](WirelessApi.md#Invoke-WirelessWirelessLansDestroy) | **DELETE** /api/wireless/wireless-lans/{id}/ | 
[**Invoke-WirelessWirelessLansList**](WirelessApi.md#Invoke-WirelessWirelessLansList) | **GET** /api/wireless/wireless-lans/ | 
[**Invoke-WirelessWirelessLansPartialUpdate**](WirelessApi.md#Invoke-WirelessWirelessLansPartialUpdate) | **PATCH** /api/wireless/wireless-lans/{id}/ | 
[**Invoke-WirelessWirelessLansRetrieve**](WirelessApi.md#Invoke-WirelessWirelessLansRetrieve) | **GET** /api/wireless/wireless-lans/{id}/ | 
[**Invoke-WirelessWirelessLansUpdate**](WirelessApi.md#Invoke-WirelessWirelessLansUpdate) | **PUT** /api/wireless/wireless-lans/{id}/ | 
[**Invoke-WirelessWirelessLinksBulkDestroy**](WirelessApi.md#Invoke-WirelessWirelessLinksBulkDestroy) | **DELETE** /api/wireless/wireless-links/ | 
[**Invoke-WirelessWirelessLinksBulkPartialUpdate**](WirelessApi.md#Invoke-WirelessWirelessLinksBulkPartialUpdate) | **PATCH** /api/wireless/wireless-links/ | 
[**Invoke-WirelessWirelessLinksBulkUpdate**](WirelessApi.md#Invoke-WirelessWirelessLinksBulkUpdate) | **PUT** /api/wireless/wireless-links/ | 
[**Invoke-WirelessWirelessLinksCreate**](WirelessApi.md#Invoke-WirelessWirelessLinksCreate) | **POST** /api/wireless/wireless-links/ | 
[**Invoke-WirelessWirelessLinksDestroy**](WirelessApi.md#Invoke-WirelessWirelessLinksDestroy) | **DELETE** /api/wireless/wireless-links/{id}/ | 
[**Invoke-WirelessWirelessLinksList**](WirelessApi.md#Invoke-WirelessWirelessLinksList) | **GET** /api/wireless/wireless-links/ | 
[**Invoke-WirelessWirelessLinksPartialUpdate**](WirelessApi.md#Invoke-WirelessWirelessLinksPartialUpdate) | **PATCH** /api/wireless/wireless-links/{id}/ | 
[**Invoke-WirelessWirelessLinksRetrieve**](WirelessApi.md#Invoke-WirelessWirelessLinksRetrieve) | **GET** /api/wireless/wireless-links/{id}/ | 
[**Invoke-WirelessWirelessLinksUpdate**](WirelessApi.md#Invoke-WirelessWirelessLinksUpdate) | **PUT** /api/wireless/wireless-links/{id}/ | 


<a id="Invoke-WirelessWirelessLanGroupsBulkDestroy"></a>
# **Invoke-WirelessWirelessLanGroupsBulkDestroy**
> void Invoke-WirelessWirelessLanGroupsBulkDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WirelessLANGroupRequest] <PSCustomObject[]><br>



Delete a list of wireless LAN group objects.

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

$NestedWirelessLANGroupRequest = Initialize-NestedWirelessLANGroupRequest -Name "MyName" -Slug "MySlug"
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WirelessLANGroupRequest = Initialize-WirelessLANGroupRequest -Name "MyName" -Slug "MySlug" -Parent $NestedWirelessLANGroupRequest -Description "MyDescription" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WirelessLANGroupRequest[] | 

try {
    $Result = Invoke-WirelessWirelessLanGroupsBulkDestroy -WirelessLANGroupRequest $WirelessLANGroupRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLanGroupsBulkDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WirelessLANGroupRequest** | [**WirelessLANGroupRequest[]**](WirelessLANGroupRequest.md)|  | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLanGroupsBulkPartialUpdate"></a>
# **Invoke-WirelessWirelessLanGroupsBulkPartialUpdate**
> WirelessLANGroup[] Invoke-WirelessWirelessLanGroupsBulkPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WirelessLANGroupRequest] <PSCustomObject[]><br>



Patch a list of wireless LAN group objects.

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

$NestedWirelessLANGroupRequest = Initialize-NestedWirelessLANGroupRequest -Name "MyName" -Slug "MySlug"
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WirelessLANGroupRequest = Initialize-WirelessLANGroupRequest -Name "MyName" -Slug "MySlug" -Parent $NestedWirelessLANGroupRequest -Description "MyDescription" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WirelessLANGroupRequest[] | 

try {
    $Result = Invoke-WirelessWirelessLanGroupsBulkPartialUpdate -WirelessLANGroupRequest $WirelessLANGroupRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLanGroupsBulkPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WirelessLANGroupRequest** | [**WirelessLANGroupRequest[]**](WirelessLANGroupRequest.md)|  | 

### Return type

[**WirelessLANGroup[]**](WirelessLANGroup.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLanGroupsBulkUpdate"></a>
# **Invoke-WirelessWirelessLanGroupsBulkUpdate**
> WirelessLANGroup[] Invoke-WirelessWirelessLanGroupsBulkUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WirelessLANGroupRequest] <PSCustomObject[]><br>



Put a list of wireless LAN group objects.

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

$NestedWirelessLANGroupRequest = Initialize-NestedWirelessLANGroupRequest -Name "MyName" -Slug "MySlug"
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WirelessLANGroupRequest = Initialize-WirelessLANGroupRequest -Name "MyName" -Slug "MySlug" -Parent $NestedWirelessLANGroupRequest -Description "MyDescription" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WirelessLANGroupRequest[] | 

try {
    $Result = Invoke-WirelessWirelessLanGroupsBulkUpdate -WirelessLANGroupRequest $WirelessLANGroupRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLanGroupsBulkUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WirelessLANGroupRequest** | [**WirelessLANGroupRequest[]**](WirelessLANGroupRequest.md)|  | 

### Return type

[**WirelessLANGroup[]**](WirelessLANGroup.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLanGroupsCreate"></a>
# **Invoke-WirelessWirelessLanGroupsCreate**
> WirelessLANGroup Invoke-WirelessWirelessLanGroupsCreate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableWirelessLANGroupRequest] <PSCustomObject><br>



Post a list of wireless LAN group objects.

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

$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WritableWirelessLANGroupRequest = Initialize-WritableWirelessLANGroupRequest -Name "MyName" -Slug "MySlug" -Parent 0 -Description "MyDescription" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WritableWirelessLANGroupRequest | 

try {
    $Result = Invoke-WirelessWirelessLanGroupsCreate -WritableWirelessLANGroupRequest $WritableWirelessLANGroupRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLanGroupsCreate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WritableWirelessLANGroupRequest** | [**WritableWirelessLANGroupRequest**](WritableWirelessLANGroupRequest.md)|  | 

### Return type

[**WirelessLANGroup**](WirelessLANGroup.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLanGroupsDestroy"></a>
# **Invoke-WirelessWirelessLanGroupsDestroy**
> void Invoke-WirelessWirelessLanGroupsDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Delete a wireless LAN group object.

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

$Id = 56 # Int32 | A unique integer value identifying this wireless LAN group.

try {
    $Result = Invoke-WirelessWirelessLanGroupsDestroy -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLanGroupsDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this wireless LAN group. | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLanGroupsList"></a>
# **Invoke-WirelessWirelessLanGroupsList**
> PaginatedWirelessLANGroupList Invoke-WirelessWirelessLanGroupsList<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Created] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedEmpty] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedGt] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedGte] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedLt] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedLte] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedN] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedByRequest] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Description] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionNisw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdated] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedEmpty] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedGt] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedGte] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedLt] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedLte] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedN] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Limit] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ModifiedByRequest] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Name] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-NameEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-NameIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-NameIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-NameIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-NameIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-NameN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-NameNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-NameNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-NameNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-NameNisw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Offset] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Ordering] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Parent] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ParentN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ParentId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ParentIdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Q] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Slug] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SlugEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SlugIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SlugIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SlugIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SlugIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SlugN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SlugNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SlugNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SlugNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SlugNisw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Tag] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TagN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UpdatedByRequest] <String><br>



Get a list of wireless LAN group objects.

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

$Created = (Get-Date) # System.DateTime[] |  (optional)
$CreatedEmpty = (Get-Date) # System.DateTime[] |  (optional)
$CreatedGt = (Get-Date) # System.DateTime[] |  (optional)
$CreatedGte = (Get-Date) # System.DateTime[] |  (optional)
$CreatedLt = (Get-Date) # System.DateTime[] |  (optional)
$CreatedLte = (Get-Date) # System.DateTime[] |  (optional)
$CreatedN = (Get-Date) # System.DateTime[] |  (optional)
$CreatedByRequest = "38400000-8cf0-11bd-b23e-10b96e4ef00d" # String |  (optional)
$Description = "MyDescription" # String[] |  (optional)
$DescriptionEmpty = $true # Boolean |  (optional)
$DescriptionIc = "MyDescriptionIc" # String[] |  (optional)
$DescriptionIe = "MyDescriptionIe" # String[] |  (optional)
$DescriptionIew = "MyDescriptionIew" # String[] |  (optional)
$DescriptionIsw = "MyDescriptionIsw" # String[] |  (optional)
$DescriptionN = "MyDescriptionN" # String[] |  (optional)
$DescriptionNic = "MyDescriptionNic" # String[] |  (optional)
$DescriptionNie = "MyDescriptionNie" # String[] |  (optional)
$DescriptionNiew = "MyDescriptionNiew" # String[] |  (optional)
$DescriptionNisw = "MyDescriptionNisw" # String[] |  (optional)
$Id = 0 # Int32[] |  (optional)
$IdEmpty = $true # Boolean |  (optional)
$IdGt = 0 # Int32[] |  (optional)
$IdGte = 0 # Int32[] |  (optional)
$IdLt = 0 # Int32[] |  (optional)
$IdLte = 0 # Int32[] |  (optional)
$IdN = 0 # Int32[] |  (optional)
$LastUpdated = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedEmpty = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedGt = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedGte = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedLt = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedLte = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedN = (Get-Date) # System.DateTime[] |  (optional)
$Limit = 56 # Int32 | Number of results to return per page. (optional)
$ModifiedByRequest = "38400000-8cf0-11bd-b23e-10b96e4ef00d" # String |  (optional)
$Name = "MyName" # String[] |  (optional)
$NameEmpty = $true # Boolean |  (optional)
$NameIc = "MyNameIc" # String[] |  (optional)
$NameIe = "MyNameIe" # String[] |  (optional)
$NameIew = "MyNameIew" # String[] |  (optional)
$NameIsw = "MyNameIsw" # String[] |  (optional)
$NameN = "MyNameN" # String[] |  (optional)
$NameNic = "MyNameNic" # String[] |  (optional)
$NameNie = "MyNameNie" # String[] |  (optional)
$NameNiew = "MyNameNiew" # String[] |  (optional)
$NameNisw = "MyNameNisw" # String[] |  (optional)
$Offset = 56 # Int32 | The initial index from which to return the results. (optional)
$Ordering = "MyOrdering" # String | Which field to use when ordering the results. (optional)
$Parent = "MyParent" # String[] |  (optional)
$ParentN = "MyParentN" # String[] |  (optional)
$ParentId = 0 # Int32[] |  (optional)
$ParentIdN = 0 # Int32[] |  (optional)
$Q = "MyQ" # String | Search (optional)
$Slug = "MySlug" # String[] |  (optional)
$SlugEmpty = $true # Boolean |  (optional)
$SlugIc = "MySlugIc" # String[] |  (optional)
$SlugIe = "MySlugIe" # String[] |  (optional)
$SlugIew = "MySlugIew" # String[] |  (optional)
$SlugIsw = "MySlugIsw" # String[] |  (optional)
$SlugN = "MySlugN" # String[] |  (optional)
$SlugNic = "MySlugNic" # String[] |  (optional)
$SlugNie = "MySlugNie" # String[] |  (optional)
$SlugNiew = "MySlugNiew" # String[] |  (optional)
$SlugNisw = "MySlugNisw" # String[] |  (optional)
$Tag = "MyTag" # String[] |  (optional)
$TagN = "MyTagN" # String[] |  (optional)
$UpdatedByRequest = "38400000-8cf0-11bd-b23e-10b96e4ef00d" # String |  (optional)

try {
    $Result = Invoke-WirelessWirelessLanGroupsList -Created $Created -CreatedEmpty $CreatedEmpty -CreatedGt $CreatedGt -CreatedGte $CreatedGte -CreatedLt $CreatedLt -CreatedLte $CreatedLte -CreatedN $CreatedN -CreatedByRequest $CreatedByRequest -Description $Description -DescriptionEmpty $DescriptionEmpty -DescriptionIc $DescriptionIc -DescriptionIe $DescriptionIe -DescriptionIew $DescriptionIew -DescriptionIsw $DescriptionIsw -DescriptionN $DescriptionN -DescriptionNic $DescriptionNic -DescriptionNie $DescriptionNie -DescriptionNiew $DescriptionNiew -DescriptionNisw $DescriptionNisw -Id $Id -IdEmpty $IdEmpty -IdGt $IdGt -IdGte $IdGte -IdLt $IdLt -IdLte $IdLte -IdN $IdN -LastUpdated $LastUpdated -LastUpdatedEmpty $LastUpdatedEmpty -LastUpdatedGt $LastUpdatedGt -LastUpdatedGte $LastUpdatedGte -LastUpdatedLt $LastUpdatedLt -LastUpdatedLte $LastUpdatedLte -LastUpdatedN $LastUpdatedN -Limit $Limit -ModifiedByRequest $ModifiedByRequest -Name $Name -NameEmpty $NameEmpty -NameIc $NameIc -NameIe $NameIe -NameIew $NameIew -NameIsw $NameIsw -NameN $NameN -NameNic $NameNic -NameNie $NameNie -NameNiew $NameNiew -NameNisw $NameNisw -Offset $Offset -Ordering $Ordering -Parent $Parent -ParentN $ParentN -ParentId $ParentId -ParentIdN $ParentIdN -Q $Q -Slug $Slug -SlugEmpty $SlugEmpty -SlugIc $SlugIc -SlugIe $SlugIe -SlugIew $SlugIew -SlugIsw $SlugIsw -SlugN $SlugN -SlugNic $SlugNic -SlugNie $SlugNie -SlugNiew $SlugNiew -SlugNisw $SlugNisw -Tag $Tag -TagN $TagN -UpdatedByRequest $UpdatedByRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLanGroupsList: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Created** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedEmpty** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedGt** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedGte** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedLt** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedLte** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedN** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedByRequest** | **String**|  | [optional] 
 **Description** | [**String[]**](String.md)|  | [optional] 
 **DescriptionEmpty** | **Boolean**|  | [optional] 
 **DescriptionIc** | [**String[]**](String.md)|  | [optional] 
 **DescriptionIe** | [**String[]**](String.md)|  | [optional] 
 **DescriptionIew** | [**String[]**](String.md)|  | [optional] 
 **DescriptionIsw** | [**String[]**](String.md)|  | [optional] 
 **DescriptionN** | [**String[]**](String.md)|  | [optional] 
 **DescriptionNic** | [**String[]**](String.md)|  | [optional] 
 **DescriptionNie** | [**String[]**](String.md)|  | [optional] 
 **DescriptionNiew** | [**String[]**](String.md)|  | [optional] 
 **DescriptionNisw** | [**String[]**](String.md)|  | [optional] 
 **Id** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdEmpty** | **Boolean**|  | [optional] 
 **IdGt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdGte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdN** | [**Int32[]**](Int32.md)|  | [optional] 
 **LastUpdated** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedEmpty** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedGt** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedGte** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedLt** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedLte** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedN** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **Limit** | **Int32**| Number of results to return per page. | [optional] 
 **ModifiedByRequest** | **String**|  | [optional] 
 **Name** | [**String[]**](String.md)|  | [optional] 
 **NameEmpty** | **Boolean**|  | [optional] 
 **NameIc** | [**String[]**](String.md)|  | [optional] 
 **NameIe** | [**String[]**](String.md)|  | [optional] 
 **NameIew** | [**String[]**](String.md)|  | [optional] 
 **NameIsw** | [**String[]**](String.md)|  | [optional] 
 **NameN** | [**String[]**](String.md)|  | [optional] 
 **NameNic** | [**String[]**](String.md)|  | [optional] 
 **NameNie** | [**String[]**](String.md)|  | [optional] 
 **NameNiew** | [**String[]**](String.md)|  | [optional] 
 **NameNisw** | [**String[]**](String.md)|  | [optional] 
 **Offset** | **Int32**| The initial index from which to return the results. | [optional] 
 **Ordering** | **String**| Which field to use when ordering the results. | [optional] 
 **Parent** | [**String[]**](String.md)|  | [optional] 
 **ParentN** | [**String[]**](String.md)|  | [optional] 
 **ParentId** | [**Int32[]**](Int32.md)|  | [optional] 
 **ParentIdN** | [**Int32[]**](Int32.md)|  | [optional] 
 **Q** | **String**| Search | [optional] 
 **Slug** | [**String[]**](String.md)|  | [optional] 
 **SlugEmpty** | **Boolean**|  | [optional] 
 **SlugIc** | [**String[]**](String.md)|  | [optional] 
 **SlugIe** | [**String[]**](String.md)|  | [optional] 
 **SlugIew** | [**String[]**](String.md)|  | [optional] 
 **SlugIsw** | [**String[]**](String.md)|  | [optional] 
 **SlugN** | [**String[]**](String.md)|  | [optional] 
 **SlugNic** | [**String[]**](String.md)|  | [optional] 
 **SlugNie** | [**String[]**](String.md)|  | [optional] 
 **SlugNiew** | [**String[]**](String.md)|  | [optional] 
 **SlugNisw** | [**String[]**](String.md)|  | [optional] 
 **Tag** | [**String[]**](String.md)|  | [optional] 
 **TagN** | [**String[]**](String.md)|  | [optional] 
 **UpdatedByRequest** | **String**|  | [optional] 

### Return type

[**PaginatedWirelessLANGroupList**](PaginatedWirelessLANGroupList.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLanGroupsPartialUpdate"></a>
# **Invoke-WirelessWirelessLanGroupsPartialUpdate**
> WirelessLANGroup Invoke-WirelessWirelessLanGroupsPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PatchedWritableWirelessLANGroupRequest] <PSCustomObject><br>



Patch a wireless LAN group object.

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

$Id = 56 # Int32 | A unique integer value identifying this wireless LAN group.
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$PatchedWritableWirelessLANGroupRequest = Initialize-PatchedWritableWirelessLANGroupRequest -Name "MyName" -Slug "MySlug" -Parent 0 -Description "MyDescription" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # PatchedWritableWirelessLANGroupRequest |  (optional)

try {
    $Result = Invoke-WirelessWirelessLanGroupsPartialUpdate -Id $Id -PatchedWritableWirelessLANGroupRequest $PatchedWritableWirelessLANGroupRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLanGroupsPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this wireless LAN group. | 
 **PatchedWritableWirelessLANGroupRequest** | [**PatchedWritableWirelessLANGroupRequest**](PatchedWritableWirelessLANGroupRequest.md)|  | [optional] 

### Return type

[**WirelessLANGroup**](WirelessLANGroup.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLanGroupsRetrieve"></a>
# **Invoke-WirelessWirelessLanGroupsRetrieve**
> WirelessLANGroup Invoke-WirelessWirelessLanGroupsRetrieve<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Get a wireless LAN group object.

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

$Id = 56 # Int32 | A unique integer value identifying this wireless LAN group.

try {
    $Result = Invoke-WirelessWirelessLanGroupsRetrieve -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLanGroupsRetrieve: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this wireless LAN group. | 

### Return type

[**WirelessLANGroup**](WirelessLANGroup.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLanGroupsUpdate"></a>
# **Invoke-WirelessWirelessLanGroupsUpdate**
> WirelessLANGroup Invoke-WirelessWirelessLanGroupsUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableWirelessLANGroupRequest] <PSCustomObject><br>



Put a wireless LAN group object.

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

$Id = 56 # Int32 | A unique integer value identifying this wireless LAN group.
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WritableWirelessLANGroupRequest = Initialize-WritableWirelessLANGroupRequest -Name "MyName" -Slug "MySlug" -Parent 0 -Description "MyDescription" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WritableWirelessLANGroupRequest | 

try {
    $Result = Invoke-WirelessWirelessLanGroupsUpdate -Id $Id -WritableWirelessLANGroupRequest $WritableWirelessLANGroupRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLanGroupsUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this wireless LAN group. | 
 **WritableWirelessLANGroupRequest** | [**WritableWirelessLANGroupRequest**](WritableWirelessLANGroupRequest.md)|  | 

### Return type

[**WirelessLANGroup**](WirelessLANGroup.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLansBulkDestroy"></a>
# **Invoke-WirelessWirelessLansBulkDestroy**
> void Invoke-WirelessWirelessLansBulkDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WirelessLANRequest] <PSCustomObject[]><br>



Delete a list of wireless LAN objects.

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

$NestedWirelessLANGroupRequest = Initialize-NestedWirelessLANGroupRequest -Name "MyName" -Slug "MySlug"
$NestedVLANRequest = Initialize-NestedVLANRequest -Vid 0 -Name "MyName"
$NestedTenantRequest = Initialize-NestedTenantRequest -Name "MyName" -Slug "MySlug"
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WirelessLANRequest = Initialize-WirelessLANRequest -Ssid "MySsid" -Description "MyDescription" -Group $NestedWirelessLANGroupRequest -Status "active" -Vlan $NestedVLANRequest -Tenant $NestedTenantRequest -AuthType "open" -AuthCipher "auto" -AuthPsk "MyAuthPsk" -Comments "MyComments" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WirelessLANRequest[] | 

try {
    $Result = Invoke-WirelessWirelessLansBulkDestroy -WirelessLANRequest $WirelessLANRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLansBulkDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WirelessLANRequest** | [**WirelessLANRequest[]**](WirelessLANRequest.md)|  | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLansBulkPartialUpdate"></a>
# **Invoke-WirelessWirelessLansBulkPartialUpdate**
> WirelessLAN[] Invoke-WirelessWirelessLansBulkPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WirelessLANRequest] <PSCustomObject[]><br>



Patch a list of wireless LAN objects.

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

$NestedWirelessLANGroupRequest = Initialize-NestedWirelessLANGroupRequest -Name "MyName" -Slug "MySlug"
$NestedVLANRequest = Initialize-NestedVLANRequest -Vid 0 -Name "MyName"
$NestedTenantRequest = Initialize-NestedTenantRequest -Name "MyName" -Slug "MySlug"
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WirelessLANRequest = Initialize-WirelessLANRequest -Ssid "MySsid" -Description "MyDescription" -Group $NestedWirelessLANGroupRequest -Status "active" -Vlan $NestedVLANRequest -Tenant $NestedTenantRequest -AuthType "open" -AuthCipher "auto" -AuthPsk "MyAuthPsk" -Comments "MyComments" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WirelessLANRequest[] | 

try {
    $Result = Invoke-WirelessWirelessLansBulkPartialUpdate -WirelessLANRequest $WirelessLANRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLansBulkPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WirelessLANRequest** | [**WirelessLANRequest[]**](WirelessLANRequest.md)|  | 

### Return type

[**WirelessLAN[]**](WirelessLAN.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLansBulkUpdate"></a>
# **Invoke-WirelessWirelessLansBulkUpdate**
> WirelessLAN[] Invoke-WirelessWirelessLansBulkUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WirelessLANRequest] <PSCustomObject[]><br>



Put a list of wireless LAN objects.

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

$NestedWirelessLANGroupRequest = Initialize-NestedWirelessLANGroupRequest -Name "MyName" -Slug "MySlug"
$NestedVLANRequest = Initialize-NestedVLANRequest -Vid 0 -Name "MyName"
$NestedTenantRequest = Initialize-NestedTenantRequest -Name "MyName" -Slug "MySlug"
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WirelessLANRequest = Initialize-WirelessLANRequest -Ssid "MySsid" -Description "MyDescription" -Group $NestedWirelessLANGroupRequest -Status "active" -Vlan $NestedVLANRequest -Tenant $NestedTenantRequest -AuthType "open" -AuthCipher "auto" -AuthPsk "MyAuthPsk" -Comments "MyComments" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WirelessLANRequest[] | 

try {
    $Result = Invoke-WirelessWirelessLansBulkUpdate -WirelessLANRequest $WirelessLANRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLansBulkUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WirelessLANRequest** | [**WirelessLANRequest[]**](WirelessLANRequest.md)|  | 

### Return type

[**WirelessLAN[]**](WirelessLAN.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLansCreate"></a>
# **Invoke-WirelessWirelessLansCreate**
> WirelessLAN Invoke-WirelessWirelessLansCreate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableWirelessLANRequest] <PSCustomObject><br>



Post a list of wireless LAN objects.

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

$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WritableWirelessLANRequest = Initialize-WritableWirelessLANRequest -Ssid "MySsid" -Description "MyDescription" -Group 0 -Status "active" -Vlan 0 -Tenant 0 -AuthType "open" -AuthCipher "auto" -AuthPsk "MyAuthPsk" -Comments "MyComments" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WritableWirelessLANRequest | 

try {
    $Result = Invoke-WirelessWirelessLansCreate -WritableWirelessLANRequest $WritableWirelessLANRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLansCreate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WritableWirelessLANRequest** | [**WritableWirelessLANRequest**](WritableWirelessLANRequest.md)|  | 

### Return type

[**WirelessLAN**](WirelessLAN.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLansDestroy"></a>
# **Invoke-WirelessWirelessLansDestroy**
> void Invoke-WirelessWirelessLansDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Delete a wireless LAN object.

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

$Id = 56 # Int32 | A unique integer value identifying this wireless LAN.

try {
    $Result = Invoke-WirelessWirelessLansDestroy -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLansDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this wireless LAN. | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLansList"></a>
# **Invoke-WirelessWirelessLansList**
> PaginatedWirelessLANList Invoke-WirelessWirelessLansList<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthCipher] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthCipherN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPsk] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskNisw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthType] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthTypeN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Created] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedEmpty] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedGt] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedGte] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedLt] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedLte] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedN] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedByRequest] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Description] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionNisw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Group] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-GroupN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-GroupId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-GroupIdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdated] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedEmpty] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedGt] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedGte] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedLt] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedLte] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedN] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Limit] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ModifiedByRequest] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Offset] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Ordering] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Q] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Ssid] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidNisw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Status] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-StatusN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Tag] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TagN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Tenant] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TenantN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TenantGroup] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TenantGroupN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TenantGroupId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TenantGroupIdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TenantId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TenantIdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UpdatedByRequest] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-VlanId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-VlanIdN] <System.Nullable[Int32][]><br>



Get a list of wireless LAN objects.

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

$AuthCipher = "MyAuthCipher" # String[] |  (optional)
$AuthCipherN = "MyAuthCipherN" # String[] |  (optional)
$AuthPsk = "MyAuthPsk" # String[] |  (optional)
$AuthPskEmpty = $true # Boolean |  (optional)
$AuthPskIc = "MyAuthPskIc" # String[] |  (optional)
$AuthPskIe = "MyAuthPskIe" # String[] |  (optional)
$AuthPskIew = "MyAuthPskIew" # String[] |  (optional)
$AuthPskIsw = "MyAuthPskIsw" # String[] |  (optional)
$AuthPskN = "MyAuthPskN" # String[] |  (optional)
$AuthPskNic = "MyAuthPskNic" # String[] |  (optional)
$AuthPskNie = "MyAuthPskNie" # String[] |  (optional)
$AuthPskNiew = "MyAuthPskNiew" # String[] |  (optional)
$AuthPskNisw = "MyAuthPskNisw" # String[] |  (optional)
$AuthType = "MyAuthType" # String[] |  (optional)
$AuthTypeN = "MyAuthTypeN" # String[] |  (optional)
$Created = (Get-Date) # System.DateTime[] |  (optional)
$CreatedEmpty = (Get-Date) # System.DateTime[] |  (optional)
$CreatedGt = (Get-Date) # System.DateTime[] |  (optional)
$CreatedGte = (Get-Date) # System.DateTime[] |  (optional)
$CreatedLt = (Get-Date) # System.DateTime[] |  (optional)
$CreatedLte = (Get-Date) # System.DateTime[] |  (optional)
$CreatedN = (Get-Date) # System.DateTime[] |  (optional)
$CreatedByRequest = "38400000-8cf0-11bd-b23e-10b96e4ef00d" # String |  (optional)
$Description = "MyDescription" # String[] |  (optional)
$DescriptionEmpty = $true # Boolean |  (optional)
$DescriptionIc = "MyDescriptionIc" # String[] |  (optional)
$DescriptionIe = "MyDescriptionIe" # String[] |  (optional)
$DescriptionIew = "MyDescriptionIew" # String[] |  (optional)
$DescriptionIsw = "MyDescriptionIsw" # String[] |  (optional)
$DescriptionN = "MyDescriptionN" # String[] |  (optional)
$DescriptionNic = "MyDescriptionNic" # String[] |  (optional)
$DescriptionNie = "MyDescriptionNie" # String[] |  (optional)
$DescriptionNiew = "MyDescriptionNiew" # String[] |  (optional)
$DescriptionNisw = "MyDescriptionNisw" # String[] |  (optional)
$Group = 0 # Int32[] |  (optional)
$GroupN = 0 # Int32[] |  (optional)
$GroupId = 0 # Int32[] |  (optional)
$GroupIdN = 0 # Int32[] |  (optional)
$Id = 0 # Int32[] |  (optional)
$IdEmpty = $true # Boolean |  (optional)
$IdGt = 0 # Int32[] |  (optional)
$IdGte = 0 # Int32[] |  (optional)
$IdLt = 0 # Int32[] |  (optional)
$IdLte = 0 # Int32[] |  (optional)
$IdN = 0 # Int32[] |  (optional)
$LastUpdated = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedEmpty = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedGt = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedGte = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedLt = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedLte = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedN = (Get-Date) # System.DateTime[] |  (optional)
$Limit = 56 # Int32 | Number of results to return per page. (optional)
$ModifiedByRequest = "38400000-8cf0-11bd-b23e-10b96e4ef00d" # String |  (optional)
$Offset = 56 # Int32 | The initial index from which to return the results. (optional)
$Ordering = "MyOrdering" # String | Which field to use when ordering the results. (optional)
$Q = "MyQ" # String | Search (optional)
$Ssid = "MySsid" # String[] |  (optional)
$SsidEmpty = $true # Boolean |  (optional)
$SsidIc = "MySsidIc" # String[] |  (optional)
$SsidIe = "MySsidIe" # String[] |  (optional)
$SsidIew = "MySsidIew" # String[] |  (optional)
$SsidIsw = "MySsidIsw" # String[] |  (optional)
$SsidN = "MySsidN" # String[] |  (optional)
$SsidNic = "MySsidNic" # String[] |  (optional)
$SsidNie = "MySsidNie" # String[] |  (optional)
$SsidNiew = "MySsidNiew" # String[] |  (optional)
$SsidNisw = "MySsidNisw" # String[] |  (optional)
$Status = "MyStatus" # String[] |  (optional)
$StatusN = "MyStatusN" # String[] |  (optional)
$Tag = "MyTag" # String[] |  (optional)
$TagN = "MyTagN" # String[] |  (optional)
$Tenant = "MyTenant" # String[] | Tenant (slug) (optional)
$TenantN = "MyTenantN" # String[] | Tenant (slug) (optional)
$TenantGroup = 0 # Int32[] | Tenant Group (slug) (optional)
$TenantGroupN = 0 # Int32[] | Tenant Group (slug) (optional)
$TenantGroupId = 0 # Int32[] | Tenant Group (ID) (optional)
$TenantGroupIdN = 0 # Int32[] | Tenant Group (ID) (optional)
$TenantId = 0 # Int32[] | Tenant (ID) (optional)
$TenantIdN = 0 # Int32[] | Tenant (ID) (optional)
$UpdatedByRequest = "38400000-8cf0-11bd-b23e-10b96e4ef00d" # String |  (optional)
$VlanId = 0 # Int32[] |  (optional)
$VlanIdN = 0 # Int32[] |  (optional)

try {
    $Result = Invoke-WirelessWirelessLansList -AuthCipher $AuthCipher -AuthCipherN $AuthCipherN -AuthPsk $AuthPsk -AuthPskEmpty $AuthPskEmpty -AuthPskIc $AuthPskIc -AuthPskIe $AuthPskIe -AuthPskIew $AuthPskIew -AuthPskIsw $AuthPskIsw -AuthPskN $AuthPskN -AuthPskNic $AuthPskNic -AuthPskNie $AuthPskNie -AuthPskNiew $AuthPskNiew -AuthPskNisw $AuthPskNisw -AuthType $AuthType -AuthTypeN $AuthTypeN -Created $Created -CreatedEmpty $CreatedEmpty -CreatedGt $CreatedGt -CreatedGte $CreatedGte -CreatedLt $CreatedLt -CreatedLte $CreatedLte -CreatedN $CreatedN -CreatedByRequest $CreatedByRequest -Description $Description -DescriptionEmpty $DescriptionEmpty -DescriptionIc $DescriptionIc -DescriptionIe $DescriptionIe -DescriptionIew $DescriptionIew -DescriptionIsw $DescriptionIsw -DescriptionN $DescriptionN -DescriptionNic $DescriptionNic -DescriptionNie $DescriptionNie -DescriptionNiew $DescriptionNiew -DescriptionNisw $DescriptionNisw -Group $Group -GroupN $GroupN -GroupId $GroupId -GroupIdN $GroupIdN -Id $Id -IdEmpty $IdEmpty -IdGt $IdGt -IdGte $IdGte -IdLt $IdLt -IdLte $IdLte -IdN $IdN -LastUpdated $LastUpdated -LastUpdatedEmpty $LastUpdatedEmpty -LastUpdatedGt $LastUpdatedGt -LastUpdatedGte $LastUpdatedGte -LastUpdatedLt $LastUpdatedLt -LastUpdatedLte $LastUpdatedLte -LastUpdatedN $LastUpdatedN -Limit $Limit -ModifiedByRequest $ModifiedByRequest -Offset $Offset -Ordering $Ordering -Q $Q -Ssid $Ssid -SsidEmpty $SsidEmpty -SsidIc $SsidIc -SsidIe $SsidIe -SsidIew $SsidIew -SsidIsw $SsidIsw -SsidN $SsidN -SsidNic $SsidNic -SsidNie $SsidNie -SsidNiew $SsidNiew -SsidNisw $SsidNisw -Status $Status -StatusN $StatusN -Tag $Tag -TagN $TagN -Tenant $Tenant -TenantN $TenantN -TenantGroup $TenantGroup -TenantGroupN $TenantGroupN -TenantGroupId $TenantGroupId -TenantGroupIdN $TenantGroupIdN -TenantId $TenantId -TenantIdN $TenantIdN -UpdatedByRequest $UpdatedByRequest -VlanId $VlanId -VlanIdN $VlanIdN
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLansList: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **AuthCipher** | [**String[]**](String.md)|  | [optional] 
 **AuthCipherN** | [**String[]**](String.md)|  | [optional] 
 **AuthPsk** | [**String[]**](String.md)|  | [optional] 
 **AuthPskEmpty** | **Boolean**|  | [optional] 
 **AuthPskIc** | [**String[]**](String.md)|  | [optional] 
 **AuthPskIe** | [**String[]**](String.md)|  | [optional] 
 **AuthPskIew** | [**String[]**](String.md)|  | [optional] 
 **AuthPskIsw** | [**String[]**](String.md)|  | [optional] 
 **AuthPskN** | [**String[]**](String.md)|  | [optional] 
 **AuthPskNic** | [**String[]**](String.md)|  | [optional] 
 **AuthPskNie** | [**String[]**](String.md)|  | [optional] 
 **AuthPskNiew** | [**String[]**](String.md)|  | [optional] 
 **AuthPskNisw** | [**String[]**](String.md)|  | [optional] 
 **AuthType** | [**String[]**](String.md)|  | [optional] 
 **AuthTypeN** | [**String[]**](String.md)|  | [optional] 
 **Created** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedEmpty** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedGt** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedGte** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedLt** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedLte** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedN** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedByRequest** | **String**|  | [optional] 
 **Description** | [**String[]**](String.md)|  | [optional] 
 **DescriptionEmpty** | **Boolean**|  | [optional] 
 **DescriptionIc** | [**String[]**](String.md)|  | [optional] 
 **DescriptionIe** | [**String[]**](String.md)|  | [optional] 
 **DescriptionIew** | [**String[]**](String.md)|  | [optional] 
 **DescriptionIsw** | [**String[]**](String.md)|  | [optional] 
 **DescriptionN** | [**String[]**](String.md)|  | [optional] 
 **DescriptionNic** | [**String[]**](String.md)|  | [optional] 
 **DescriptionNie** | [**String[]**](String.md)|  | [optional] 
 **DescriptionNiew** | [**String[]**](String.md)|  | [optional] 
 **DescriptionNisw** | [**String[]**](String.md)|  | [optional] 
 **Group** | [**Int32[]**](Int32.md)|  | [optional] 
 **GroupN** | [**Int32[]**](Int32.md)|  | [optional] 
 **GroupId** | [**Int32[]**](Int32.md)|  | [optional] 
 **GroupIdN** | [**Int32[]**](Int32.md)|  | [optional] 
 **Id** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdEmpty** | **Boolean**|  | [optional] 
 **IdGt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdGte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdN** | [**Int32[]**](Int32.md)|  | [optional] 
 **LastUpdated** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedEmpty** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedGt** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedGte** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedLt** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedLte** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedN** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **Limit** | **Int32**| Number of results to return per page. | [optional] 
 **ModifiedByRequest** | **String**|  | [optional] 
 **Offset** | **Int32**| The initial index from which to return the results. | [optional] 
 **Ordering** | **String**| Which field to use when ordering the results. | [optional] 
 **Q** | **String**| Search | [optional] 
 **Ssid** | [**String[]**](String.md)|  | [optional] 
 **SsidEmpty** | **Boolean**|  | [optional] 
 **SsidIc** | [**String[]**](String.md)|  | [optional] 
 **SsidIe** | [**String[]**](String.md)|  | [optional] 
 **SsidIew** | [**String[]**](String.md)|  | [optional] 
 **SsidIsw** | [**String[]**](String.md)|  | [optional] 
 **SsidN** | [**String[]**](String.md)|  | [optional] 
 **SsidNic** | [**String[]**](String.md)|  | [optional] 
 **SsidNie** | [**String[]**](String.md)|  | [optional] 
 **SsidNiew** | [**String[]**](String.md)|  | [optional] 
 **SsidNisw** | [**String[]**](String.md)|  | [optional] 
 **Status** | [**String[]**](String.md)|  | [optional] 
 **StatusN** | [**String[]**](String.md)|  | [optional] 
 **Tag** | [**String[]**](String.md)|  | [optional] 
 **TagN** | [**String[]**](String.md)|  | [optional] 
 **Tenant** | [**String[]**](String.md)| Tenant (slug) | [optional] 
 **TenantN** | [**String[]**](String.md)| Tenant (slug) | [optional] 
 **TenantGroup** | [**Int32[]**](Int32.md)| Tenant Group (slug) | [optional] 
 **TenantGroupN** | [**Int32[]**](Int32.md)| Tenant Group (slug) | [optional] 
 **TenantGroupId** | [**Int32[]**](Int32.md)| Tenant Group (ID) | [optional] 
 **TenantGroupIdN** | [**Int32[]**](Int32.md)| Tenant Group (ID) | [optional] 
 **TenantId** | [**Int32[]**](Int32.md)| Tenant (ID) | [optional] 
 **TenantIdN** | [**Int32[]**](Int32.md)| Tenant (ID) | [optional] 
 **UpdatedByRequest** | **String**|  | [optional] 
 **VlanId** | [**Int32[]**](Int32.md)|  | [optional] 
 **VlanIdN** | [**Int32[]**](Int32.md)|  | [optional] 

### Return type

[**PaginatedWirelessLANList**](PaginatedWirelessLANList.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLansPartialUpdate"></a>
# **Invoke-WirelessWirelessLansPartialUpdate**
> WirelessLAN Invoke-WirelessWirelessLansPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PatchedWritableWirelessLANRequest] <PSCustomObject><br>



Patch a wireless LAN object.

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

$Id = 56 # Int32 | A unique integer value identifying this wireless LAN.
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$PatchedWritableWirelessLANRequest = Initialize-PatchedWritableWirelessLANRequest -Ssid "MySsid" -Description "MyDescription" -Group 0 -Status "active" -Vlan 0 -Tenant 0 -AuthType "open" -AuthCipher "auto" -AuthPsk "MyAuthPsk" -Comments "MyComments" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # PatchedWritableWirelessLANRequest |  (optional)

try {
    $Result = Invoke-WirelessWirelessLansPartialUpdate -Id $Id -PatchedWritableWirelessLANRequest $PatchedWritableWirelessLANRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLansPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this wireless LAN. | 
 **PatchedWritableWirelessLANRequest** | [**PatchedWritableWirelessLANRequest**](PatchedWritableWirelessLANRequest.md)|  | [optional] 

### Return type

[**WirelessLAN**](WirelessLAN.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLansRetrieve"></a>
# **Invoke-WirelessWirelessLansRetrieve**
> WirelessLAN Invoke-WirelessWirelessLansRetrieve<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Get a wireless LAN object.

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

$Id = 56 # Int32 | A unique integer value identifying this wireless LAN.

try {
    $Result = Invoke-WirelessWirelessLansRetrieve -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLansRetrieve: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this wireless LAN. | 

### Return type

[**WirelessLAN**](WirelessLAN.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLansUpdate"></a>
# **Invoke-WirelessWirelessLansUpdate**
> WirelessLAN Invoke-WirelessWirelessLansUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableWirelessLANRequest] <PSCustomObject><br>



Put a wireless LAN object.

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

$Id = 56 # Int32 | A unique integer value identifying this wireless LAN.
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WritableWirelessLANRequest = Initialize-WritableWirelessLANRequest -Ssid "MySsid" -Description "MyDescription" -Group 0 -Status "active" -Vlan 0 -Tenant 0 -AuthType "open" -AuthCipher "auto" -AuthPsk "MyAuthPsk" -Comments "MyComments" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WritableWirelessLANRequest | 

try {
    $Result = Invoke-WirelessWirelessLansUpdate -Id $Id -WritableWirelessLANRequest $WritableWirelessLANRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLansUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this wireless LAN. | 
 **WritableWirelessLANRequest** | [**WritableWirelessLANRequest**](WritableWirelessLANRequest.md)|  | 

### Return type

[**WirelessLAN**](WirelessLAN.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLinksBulkDestroy"></a>
# **Invoke-WirelessWirelessLinksBulkDestroy**
> void Invoke-WirelessWirelessLinksBulkDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WirelessLinkRequest] <PSCustomObject[]><br>



Delete a list of wireless link objects.

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

$NestedInterfaceRequest = Initialize-NestedInterfaceRequest -Name "MyName" -Cable 0
$NestedTenantRequest = Initialize-NestedTenantRequest -Name "MyName" -Slug "MySlug"
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WirelessLinkRequest = Initialize-WirelessLinkRequest -InterfaceA $NestedInterfaceRequest -InterfaceB $NestedInterfaceRequest -Ssid "MySsid" -Status "connected" -Tenant $NestedTenantRequest -AuthType "open" -AuthCipher "auto" -AuthPsk "MyAuthPsk" -Description "MyDescription" -Comments "MyComments" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WirelessLinkRequest[] | 

try {
    $Result = Invoke-WirelessWirelessLinksBulkDestroy -WirelessLinkRequest $WirelessLinkRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLinksBulkDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WirelessLinkRequest** | [**WirelessLinkRequest[]**](WirelessLinkRequest.md)|  | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLinksBulkPartialUpdate"></a>
# **Invoke-WirelessWirelessLinksBulkPartialUpdate**
> WirelessLink[] Invoke-WirelessWirelessLinksBulkPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WirelessLinkRequest] <PSCustomObject[]><br>



Patch a list of wireless link objects.

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

$NestedInterfaceRequest = Initialize-NestedInterfaceRequest -Name "MyName" -Cable 0
$NestedTenantRequest = Initialize-NestedTenantRequest -Name "MyName" -Slug "MySlug"
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WirelessLinkRequest = Initialize-WirelessLinkRequest -InterfaceA $NestedInterfaceRequest -InterfaceB $NestedInterfaceRequest -Ssid "MySsid" -Status "connected" -Tenant $NestedTenantRequest -AuthType "open" -AuthCipher "auto" -AuthPsk "MyAuthPsk" -Description "MyDescription" -Comments "MyComments" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WirelessLinkRequest[] | 

try {
    $Result = Invoke-WirelessWirelessLinksBulkPartialUpdate -WirelessLinkRequest $WirelessLinkRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLinksBulkPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WirelessLinkRequest** | [**WirelessLinkRequest[]**](WirelessLinkRequest.md)|  | 

### Return type

[**WirelessLink[]**](WirelessLink.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLinksBulkUpdate"></a>
# **Invoke-WirelessWirelessLinksBulkUpdate**
> WirelessLink[] Invoke-WirelessWirelessLinksBulkUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WirelessLinkRequest] <PSCustomObject[]><br>



Put a list of wireless link objects.

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

$NestedInterfaceRequest = Initialize-NestedInterfaceRequest -Name "MyName" -Cable 0
$NestedTenantRequest = Initialize-NestedTenantRequest -Name "MyName" -Slug "MySlug"
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WirelessLinkRequest = Initialize-WirelessLinkRequest -InterfaceA $NestedInterfaceRequest -InterfaceB $NestedInterfaceRequest -Ssid "MySsid" -Status "connected" -Tenant $NestedTenantRequest -AuthType "open" -AuthCipher "auto" -AuthPsk "MyAuthPsk" -Description "MyDescription" -Comments "MyComments" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WirelessLinkRequest[] | 

try {
    $Result = Invoke-WirelessWirelessLinksBulkUpdate -WirelessLinkRequest $WirelessLinkRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLinksBulkUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WirelessLinkRequest** | [**WirelessLinkRequest[]**](WirelessLinkRequest.md)|  | 

### Return type

[**WirelessLink[]**](WirelessLink.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLinksCreate"></a>
# **Invoke-WirelessWirelessLinksCreate**
> WirelessLink Invoke-WirelessWirelessLinksCreate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableWirelessLinkRequest] <PSCustomObject><br>



Post a list of wireless link objects.

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

$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WritableWirelessLinkRequest = Initialize-WritableWirelessLinkRequest -InterfaceA 0 -InterfaceB 0 -Ssid "MySsid" -Status "connected" -Tenant 0 -AuthType "open" -AuthCipher "auto" -AuthPsk "MyAuthPsk" -Description "MyDescription" -Comments "MyComments" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WritableWirelessLinkRequest | 

try {
    $Result = Invoke-WirelessWirelessLinksCreate -WritableWirelessLinkRequest $WritableWirelessLinkRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLinksCreate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WritableWirelessLinkRequest** | [**WritableWirelessLinkRequest**](WritableWirelessLinkRequest.md)|  | 

### Return type

[**WirelessLink**](WirelessLink.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLinksDestroy"></a>
# **Invoke-WirelessWirelessLinksDestroy**
> void Invoke-WirelessWirelessLinksDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Delete a wireless link object.

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

$Id = 56 # Int32 | A unique integer value identifying this wireless link.

try {
    $Result = Invoke-WirelessWirelessLinksDestroy -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLinksDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this wireless link. | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLinksList"></a>
# **Invoke-WirelessWirelessLinksList**
> PaginatedWirelessLinkList Invoke-WirelessWirelessLinksList<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthCipher] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthCipherN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPsk] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthPskNisw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthType] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-AuthTypeN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Created] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedEmpty] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedGt] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedGte] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedLt] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedLte] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedN] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedByRequest] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Description] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DescriptionNisw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-InterfaceAId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-InterfaceAIdEmpty] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-InterfaceAIdGt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-InterfaceAIdGte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-InterfaceAIdLt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-InterfaceAIdLte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-InterfaceAIdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-InterfaceBId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-InterfaceBIdEmpty] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-InterfaceBIdGt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-InterfaceBIdGte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-InterfaceBIdLt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-InterfaceBIdLte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-InterfaceBIdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdated] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedEmpty] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedGt] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedGte] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedLt] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedLte] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastUpdatedN] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Limit] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ModifiedByRequest] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Offset] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Ordering] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Q] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Ssid] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SsidNisw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Status] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-StatusN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Tag] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TagN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Tenant] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TenantN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TenantGroup] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TenantGroupN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TenantGroupId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TenantGroupIdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TenantId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TenantIdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UpdatedByRequest] <String><br>



Get a list of wireless link objects.

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

$AuthCipher = "MyAuthCipher" # String[] |  (optional)
$AuthCipherN = "MyAuthCipherN" # String[] |  (optional)
$AuthPsk = "MyAuthPsk" # String[] |  (optional)
$AuthPskEmpty = $true # Boolean |  (optional)
$AuthPskIc = "MyAuthPskIc" # String[] |  (optional)
$AuthPskIe = "MyAuthPskIe" # String[] |  (optional)
$AuthPskIew = "MyAuthPskIew" # String[] |  (optional)
$AuthPskIsw = "MyAuthPskIsw" # String[] |  (optional)
$AuthPskN = "MyAuthPskN" # String[] |  (optional)
$AuthPskNic = "MyAuthPskNic" # String[] |  (optional)
$AuthPskNie = "MyAuthPskNie" # String[] |  (optional)
$AuthPskNiew = "MyAuthPskNiew" # String[] |  (optional)
$AuthPskNisw = "MyAuthPskNisw" # String[] |  (optional)
$AuthType = "MyAuthType" # String[] |  (optional)
$AuthTypeN = "MyAuthTypeN" # String[] |  (optional)
$Created = (Get-Date) # System.DateTime[] |  (optional)
$CreatedEmpty = (Get-Date) # System.DateTime[] |  (optional)
$CreatedGt = (Get-Date) # System.DateTime[] |  (optional)
$CreatedGte = (Get-Date) # System.DateTime[] |  (optional)
$CreatedLt = (Get-Date) # System.DateTime[] |  (optional)
$CreatedLte = (Get-Date) # System.DateTime[] |  (optional)
$CreatedN = (Get-Date) # System.DateTime[] |  (optional)
$CreatedByRequest = "38400000-8cf0-11bd-b23e-10b96e4ef00d" # String |  (optional)
$Description = "MyDescription" # String[] |  (optional)
$DescriptionEmpty = $true # Boolean |  (optional)
$DescriptionIc = "MyDescriptionIc" # String[] |  (optional)
$DescriptionIe = "MyDescriptionIe" # String[] |  (optional)
$DescriptionIew = "MyDescriptionIew" # String[] |  (optional)
$DescriptionIsw = "MyDescriptionIsw" # String[] |  (optional)
$DescriptionN = "MyDescriptionN" # String[] |  (optional)
$DescriptionNic = "MyDescriptionNic" # String[] |  (optional)
$DescriptionNie = "MyDescriptionNie" # String[] |  (optional)
$DescriptionNiew = "MyDescriptionNiew" # String[] |  (optional)
$DescriptionNisw = "MyDescriptionNisw" # String[] |  (optional)
$Id = 0 # Int32[] |  (optional)
$IdEmpty = $true # Boolean |  (optional)
$IdGt = 0 # Int32[] |  (optional)
$IdGte = 0 # Int32[] |  (optional)
$IdLt = 0 # Int32[] |  (optional)
$IdLte = 0 # Int32[] |  (optional)
$IdN = 0 # Int32[] |  (optional)
$InterfaceAId = 0 # Int32[] |  (optional)
$InterfaceAIdEmpty = 0 # Int32[] |  (optional)
$InterfaceAIdGt = 0 # Int32[] |  (optional)
$InterfaceAIdGte = 0 # Int32[] |  (optional)
$InterfaceAIdLt = 0 # Int32[] |  (optional)
$InterfaceAIdLte = 0 # Int32[] |  (optional)
$InterfaceAIdN = 0 # Int32[] |  (optional)
$InterfaceBId = 0 # Int32[] |  (optional)
$InterfaceBIdEmpty = 0 # Int32[] |  (optional)
$InterfaceBIdGt = 0 # Int32[] |  (optional)
$InterfaceBIdGte = 0 # Int32[] |  (optional)
$InterfaceBIdLt = 0 # Int32[] |  (optional)
$InterfaceBIdLte = 0 # Int32[] |  (optional)
$InterfaceBIdN = 0 # Int32[] |  (optional)
$LastUpdated = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedEmpty = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedGt = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedGte = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedLt = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedLte = (Get-Date) # System.DateTime[] |  (optional)
$LastUpdatedN = (Get-Date) # System.DateTime[] |  (optional)
$Limit = 56 # Int32 | Number of results to return per page. (optional)
$ModifiedByRequest = "38400000-8cf0-11bd-b23e-10b96e4ef00d" # String |  (optional)
$Offset = 56 # Int32 | The initial index from which to return the results. (optional)
$Ordering = "MyOrdering" # String | Which field to use when ordering the results. (optional)
$Q = "MyQ" # String | Search (optional)
$Ssid = "MySsid" # String[] |  (optional)
$SsidEmpty = $true # Boolean |  (optional)
$SsidIc = "MySsidIc" # String[] |  (optional)
$SsidIe = "MySsidIe" # String[] |  (optional)
$SsidIew = "MySsidIew" # String[] |  (optional)
$SsidIsw = "MySsidIsw" # String[] |  (optional)
$SsidN = "MySsidN" # String[] |  (optional)
$SsidNic = "MySsidNic" # String[] |  (optional)
$SsidNie = "MySsidNie" # String[] |  (optional)
$SsidNiew = "MySsidNiew" # String[] |  (optional)
$SsidNisw = "MySsidNisw" # String[] |  (optional)
$Status = "MyStatus" # String[] |  (optional)
$StatusN = "MyStatusN" # String[] |  (optional)
$Tag = "MyTag" # String[] |  (optional)
$TagN = "MyTagN" # String[] |  (optional)
$Tenant = "MyTenant" # String[] | Tenant (slug) (optional)
$TenantN = "MyTenantN" # String[] | Tenant (slug) (optional)
$TenantGroup = 0 # Int32[] | Tenant Group (slug) (optional)
$TenantGroupN = 0 # Int32[] | Tenant Group (slug) (optional)
$TenantGroupId = 0 # Int32[] | Tenant Group (ID) (optional)
$TenantGroupIdN = 0 # Int32[] | Tenant Group (ID) (optional)
$TenantId = 0 # Int32[] | Tenant (ID) (optional)
$TenantIdN = 0 # Int32[] | Tenant (ID) (optional)
$UpdatedByRequest = "38400000-8cf0-11bd-b23e-10b96e4ef00d" # String |  (optional)

try {
    $Result = Invoke-WirelessWirelessLinksList -AuthCipher $AuthCipher -AuthCipherN $AuthCipherN -AuthPsk $AuthPsk -AuthPskEmpty $AuthPskEmpty -AuthPskIc $AuthPskIc -AuthPskIe $AuthPskIe -AuthPskIew $AuthPskIew -AuthPskIsw $AuthPskIsw -AuthPskN $AuthPskN -AuthPskNic $AuthPskNic -AuthPskNie $AuthPskNie -AuthPskNiew $AuthPskNiew -AuthPskNisw $AuthPskNisw -AuthType $AuthType -AuthTypeN $AuthTypeN -Created $Created -CreatedEmpty $CreatedEmpty -CreatedGt $CreatedGt -CreatedGte $CreatedGte -CreatedLt $CreatedLt -CreatedLte $CreatedLte -CreatedN $CreatedN -CreatedByRequest $CreatedByRequest -Description $Description -DescriptionEmpty $DescriptionEmpty -DescriptionIc $DescriptionIc -DescriptionIe $DescriptionIe -DescriptionIew $DescriptionIew -DescriptionIsw $DescriptionIsw -DescriptionN $DescriptionN -DescriptionNic $DescriptionNic -DescriptionNie $DescriptionNie -DescriptionNiew $DescriptionNiew -DescriptionNisw $DescriptionNisw -Id $Id -IdEmpty $IdEmpty -IdGt $IdGt -IdGte $IdGte -IdLt $IdLt -IdLte $IdLte -IdN $IdN -InterfaceAId $InterfaceAId -InterfaceAIdEmpty $InterfaceAIdEmpty -InterfaceAIdGt $InterfaceAIdGt -InterfaceAIdGte $InterfaceAIdGte -InterfaceAIdLt $InterfaceAIdLt -InterfaceAIdLte $InterfaceAIdLte -InterfaceAIdN $InterfaceAIdN -InterfaceBId $InterfaceBId -InterfaceBIdEmpty $InterfaceBIdEmpty -InterfaceBIdGt $InterfaceBIdGt -InterfaceBIdGte $InterfaceBIdGte -InterfaceBIdLt $InterfaceBIdLt -InterfaceBIdLte $InterfaceBIdLte -InterfaceBIdN $InterfaceBIdN -LastUpdated $LastUpdated -LastUpdatedEmpty $LastUpdatedEmpty -LastUpdatedGt $LastUpdatedGt -LastUpdatedGte $LastUpdatedGte -LastUpdatedLt $LastUpdatedLt -LastUpdatedLte $LastUpdatedLte -LastUpdatedN $LastUpdatedN -Limit $Limit -ModifiedByRequest $ModifiedByRequest -Offset $Offset -Ordering $Ordering -Q $Q -Ssid $Ssid -SsidEmpty $SsidEmpty -SsidIc $SsidIc -SsidIe $SsidIe -SsidIew $SsidIew -SsidIsw $SsidIsw -SsidN $SsidN -SsidNic $SsidNic -SsidNie $SsidNie -SsidNiew $SsidNiew -SsidNisw $SsidNisw -Status $Status -StatusN $StatusN -Tag $Tag -TagN $TagN -Tenant $Tenant -TenantN $TenantN -TenantGroup $TenantGroup -TenantGroupN $TenantGroupN -TenantGroupId $TenantGroupId -TenantGroupIdN $TenantGroupIdN -TenantId $TenantId -TenantIdN $TenantIdN -UpdatedByRequest $UpdatedByRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLinksList: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **AuthCipher** | [**String[]**](String.md)|  | [optional] 
 **AuthCipherN** | [**String[]**](String.md)|  | [optional] 
 **AuthPsk** | [**String[]**](String.md)|  | [optional] 
 **AuthPskEmpty** | **Boolean**|  | [optional] 
 **AuthPskIc** | [**String[]**](String.md)|  | [optional] 
 **AuthPskIe** | [**String[]**](String.md)|  | [optional] 
 **AuthPskIew** | [**String[]**](String.md)|  | [optional] 
 **AuthPskIsw** | [**String[]**](String.md)|  | [optional] 
 **AuthPskN** | [**String[]**](String.md)|  | [optional] 
 **AuthPskNic** | [**String[]**](String.md)|  | [optional] 
 **AuthPskNie** | [**String[]**](String.md)|  | [optional] 
 **AuthPskNiew** | [**String[]**](String.md)|  | [optional] 
 **AuthPskNisw** | [**String[]**](String.md)|  | [optional] 
 **AuthType** | [**String[]**](String.md)|  | [optional] 
 **AuthTypeN** | [**String[]**](String.md)|  | [optional] 
 **Created** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedEmpty** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedGt** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedGte** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedLt** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedLte** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedN** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **CreatedByRequest** | **String**|  | [optional] 
 **Description** | [**String[]**](String.md)|  | [optional] 
 **DescriptionEmpty** | **Boolean**|  | [optional] 
 **DescriptionIc** | [**String[]**](String.md)|  | [optional] 
 **DescriptionIe** | [**String[]**](String.md)|  | [optional] 
 **DescriptionIew** | [**String[]**](String.md)|  | [optional] 
 **DescriptionIsw** | [**String[]**](String.md)|  | [optional] 
 **DescriptionN** | [**String[]**](String.md)|  | [optional] 
 **DescriptionNic** | [**String[]**](String.md)|  | [optional] 
 **DescriptionNie** | [**String[]**](String.md)|  | [optional] 
 **DescriptionNiew** | [**String[]**](String.md)|  | [optional] 
 **DescriptionNisw** | [**String[]**](String.md)|  | [optional] 
 **Id** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdEmpty** | **Boolean**|  | [optional] 
 **IdGt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdGte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdN** | [**Int32[]**](Int32.md)|  | [optional] 
 **InterfaceAId** | [**Int32[]**](Int32.md)|  | [optional] 
 **InterfaceAIdEmpty** | [**Int32[]**](Int32.md)|  | [optional] 
 **InterfaceAIdGt** | [**Int32[]**](Int32.md)|  | [optional] 
 **InterfaceAIdGte** | [**Int32[]**](Int32.md)|  | [optional] 
 **InterfaceAIdLt** | [**Int32[]**](Int32.md)|  | [optional] 
 **InterfaceAIdLte** | [**Int32[]**](Int32.md)|  | [optional] 
 **InterfaceAIdN** | [**Int32[]**](Int32.md)|  | [optional] 
 **InterfaceBId** | [**Int32[]**](Int32.md)|  | [optional] 
 **InterfaceBIdEmpty** | [**Int32[]**](Int32.md)|  | [optional] 
 **InterfaceBIdGt** | [**Int32[]**](Int32.md)|  | [optional] 
 **InterfaceBIdGte** | [**Int32[]**](Int32.md)|  | [optional] 
 **InterfaceBIdLt** | [**Int32[]**](Int32.md)|  | [optional] 
 **InterfaceBIdLte** | [**Int32[]**](Int32.md)|  | [optional] 
 **InterfaceBIdN** | [**Int32[]**](Int32.md)|  | [optional] 
 **LastUpdated** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedEmpty** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedGt** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedGte** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedLt** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedLte** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **LastUpdatedN** | [**System.DateTime[]**](System.DateTime.md)|  | [optional] 
 **Limit** | **Int32**| Number of results to return per page. | [optional] 
 **ModifiedByRequest** | **String**|  | [optional] 
 **Offset** | **Int32**| The initial index from which to return the results. | [optional] 
 **Ordering** | **String**| Which field to use when ordering the results. | [optional] 
 **Q** | **String**| Search | [optional] 
 **Ssid** | [**String[]**](String.md)|  | [optional] 
 **SsidEmpty** | **Boolean**|  | [optional] 
 **SsidIc** | [**String[]**](String.md)|  | [optional] 
 **SsidIe** | [**String[]**](String.md)|  | [optional] 
 **SsidIew** | [**String[]**](String.md)|  | [optional] 
 **SsidIsw** | [**String[]**](String.md)|  | [optional] 
 **SsidN** | [**String[]**](String.md)|  | [optional] 
 **SsidNic** | [**String[]**](String.md)|  | [optional] 
 **SsidNie** | [**String[]**](String.md)|  | [optional] 
 **SsidNiew** | [**String[]**](String.md)|  | [optional] 
 **SsidNisw** | [**String[]**](String.md)|  | [optional] 
 **Status** | [**String[]**](String.md)|  | [optional] 
 **StatusN** | [**String[]**](String.md)|  | [optional] 
 **Tag** | [**String[]**](String.md)|  | [optional] 
 **TagN** | [**String[]**](String.md)|  | [optional] 
 **Tenant** | [**String[]**](String.md)| Tenant (slug) | [optional] 
 **TenantN** | [**String[]**](String.md)| Tenant (slug) | [optional] 
 **TenantGroup** | [**Int32[]**](Int32.md)| Tenant Group (slug) | [optional] 
 **TenantGroupN** | [**Int32[]**](Int32.md)| Tenant Group (slug) | [optional] 
 **TenantGroupId** | [**Int32[]**](Int32.md)| Tenant Group (ID) | [optional] 
 **TenantGroupIdN** | [**Int32[]**](Int32.md)| Tenant Group (ID) | [optional] 
 **TenantId** | [**Int32[]**](Int32.md)| Tenant (ID) | [optional] 
 **TenantIdN** | [**Int32[]**](Int32.md)| Tenant (ID) | [optional] 
 **UpdatedByRequest** | **String**|  | [optional] 

### Return type

[**PaginatedWirelessLinkList**](PaginatedWirelessLinkList.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLinksPartialUpdate"></a>
# **Invoke-WirelessWirelessLinksPartialUpdate**
> WirelessLink Invoke-WirelessWirelessLinksPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PatchedWritableWirelessLinkRequest] <PSCustomObject><br>



Patch a wireless link object.

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

$Id = 56 # Int32 | A unique integer value identifying this wireless link.
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$PatchedWritableWirelessLinkRequest = Initialize-PatchedWritableWirelessLinkRequest -InterfaceA 0 -InterfaceB 0 -Ssid "MySsid" -Status "connected" -Tenant 0 -AuthType "open" -AuthCipher "auto" -AuthPsk "MyAuthPsk" -Description "MyDescription" -Comments "MyComments" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # PatchedWritableWirelessLinkRequest |  (optional)

try {
    $Result = Invoke-WirelessWirelessLinksPartialUpdate -Id $Id -PatchedWritableWirelessLinkRequest $PatchedWritableWirelessLinkRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLinksPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this wireless link. | 
 **PatchedWritableWirelessLinkRequest** | [**PatchedWritableWirelessLinkRequest**](PatchedWritableWirelessLinkRequest.md)|  | [optional] 

### Return type

[**WirelessLink**](WirelessLink.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLinksRetrieve"></a>
# **Invoke-WirelessWirelessLinksRetrieve**
> WirelessLink Invoke-WirelessWirelessLinksRetrieve<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Get a wireless link object.

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

$Id = 56 # Int32 | A unique integer value identifying this wireless link.

try {
    $Result = Invoke-WirelessWirelessLinksRetrieve -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLinksRetrieve: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this wireless link. | 

### Return type

[**WirelessLink**](WirelessLink.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-WirelessWirelessLinksUpdate"></a>
# **Invoke-WirelessWirelessLinksUpdate**
> WirelessLink Invoke-WirelessWirelessLinksUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableWirelessLinkRequest] <PSCustomObject><br>



Put a wireless link object.

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

$Id = 56 # Int32 | A unique integer value identifying this wireless link.
$NestedTagRequest = Initialize-NestedTagRequest -Name "MyName" -Slug "MySlug" -Color "MyColor"
$WritableWirelessLinkRequest = Initialize-WritableWirelessLinkRequest -InterfaceA 0 -InterfaceB 0 -Ssid "MySsid" -Status "connected" -Tenant 0 -AuthType "open" -AuthCipher "auto" -AuthPsk "MyAuthPsk" -Description "MyDescription" -Comments "MyComments" -Tags $NestedTagRequest -CustomFields @{ key_example =  } # WritableWirelessLinkRequest | 

try {
    $Result = Invoke-WirelessWirelessLinksUpdate -Id $Id -WritableWirelessLinkRequest $WritableWirelessLinkRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-WirelessWirelessLinksUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this wireless link. | 
 **WritableWirelessLinkRequest** | [**WritableWirelessLinkRequest**](WritableWirelessLinkRequest.md)|  | 

### Return type

[**WirelessLink**](WirelessLink.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

