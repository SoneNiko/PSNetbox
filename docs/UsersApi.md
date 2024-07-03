# PSOpenAPITools.PSOpenAPITools\Api.UsersApi

All URIs are relative to *https://netbox.grid.uchicago.edu/api/schema*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Use-rsConfigRetrieve**](UsersApi.md#Use-rsConfigRetrieve) | **GET** /api/users/config/ | 
[**Use-rsGroupsBulkDestroy**](UsersApi.md#Use-rsGroupsBulkDestroy) | **DELETE** /api/users/groups/ | 
[**Use-rsGroupsBulkPartialUpdate**](UsersApi.md#Use-rsGroupsBulkPartialUpdate) | **PATCH** /api/users/groups/ | 
[**Use-rsGroupsBulkUpdate**](UsersApi.md#Use-rsGroupsBulkUpdate) | **PUT** /api/users/groups/ | 
[**Use-rsGroupsCreate**](UsersApi.md#Use-rsGroupsCreate) | **POST** /api/users/groups/ | 
[**Use-rsGroupsDestroy**](UsersApi.md#Use-rsGroupsDestroy) | **DELETE** /api/users/groups/{id}/ | 
[**Use-rsGroupsList**](UsersApi.md#Use-rsGroupsList) | **GET** /api/users/groups/ | 
[**Use-rsGroupsPartialUpdate**](UsersApi.md#Use-rsGroupsPartialUpdate) | **PATCH** /api/users/groups/{id}/ | 
[**Use-rsGroupsRetrieve**](UsersApi.md#Use-rsGroupsRetrieve) | **GET** /api/users/groups/{id}/ | 
[**Use-rsGroupsUpdate**](UsersApi.md#Use-rsGroupsUpdate) | **PUT** /api/users/groups/{id}/ | 
[**Use-rsPermissionsBulkDestroy**](UsersApi.md#Use-rsPermissionsBulkDestroy) | **DELETE** /api/users/permissions/ | 
[**Use-rsPermissionsBulkPartialUpdate**](UsersApi.md#Use-rsPermissionsBulkPartialUpdate) | **PATCH** /api/users/permissions/ | 
[**Use-rsPermissionsBulkUpdate**](UsersApi.md#Use-rsPermissionsBulkUpdate) | **PUT** /api/users/permissions/ | 
[**Use-rsPermissionsCreate**](UsersApi.md#Use-rsPermissionsCreate) | **POST** /api/users/permissions/ | 
[**Use-rsPermissionsDestroy**](UsersApi.md#Use-rsPermissionsDestroy) | **DELETE** /api/users/permissions/{id}/ | 
[**Use-rsPermissionsList**](UsersApi.md#Use-rsPermissionsList) | **GET** /api/users/permissions/ | 
[**Use-rsPermissionsPartialUpdate**](UsersApi.md#Use-rsPermissionsPartialUpdate) | **PATCH** /api/users/permissions/{id}/ | 
[**Use-rsPermissionsRetrieve**](UsersApi.md#Use-rsPermissionsRetrieve) | **GET** /api/users/permissions/{id}/ | 
[**Use-rsPermissionsUpdate**](UsersApi.md#Use-rsPermissionsUpdate) | **PUT** /api/users/permissions/{id}/ | 
[**Use-rsTokensBulkDestroy**](UsersApi.md#Use-rsTokensBulkDestroy) | **DELETE** /api/users/tokens/ | 
[**Use-rsTokensBulkPartialUpdate**](UsersApi.md#Use-rsTokensBulkPartialUpdate) | **PATCH** /api/users/tokens/ | 
[**Use-rsTokensBulkUpdate**](UsersApi.md#Use-rsTokensBulkUpdate) | **PUT** /api/users/tokens/ | 
[**Use-rsTokensCreate**](UsersApi.md#Use-rsTokensCreate) | **POST** /api/users/tokens/ | 
[**Use-rsTokensDestroy**](UsersApi.md#Use-rsTokensDestroy) | **DELETE** /api/users/tokens/{id}/ | 
[**Use-rsTokensList**](UsersApi.md#Use-rsTokensList) | **GET** /api/users/tokens/ | 
[**Use-rsTokensPartialUpdate**](UsersApi.md#Use-rsTokensPartialUpdate) | **PATCH** /api/users/tokens/{id}/ | 
[**Use-rsTokensProvisionCreate**](UsersApi.md#Use-rsTokensProvisionCreate) | **POST** /api/users/tokens/provision/ | 
[**Use-rsTokensRetrieve**](UsersApi.md#Use-rsTokensRetrieve) | **GET** /api/users/tokens/{id}/ | 
[**Use-rsTokensUpdate**](UsersApi.md#Use-rsTokensUpdate) | **PUT** /api/users/tokens/{id}/ | 
[**Use-rsUsersBulkDestroy**](UsersApi.md#Use-rsUsersBulkDestroy) | **DELETE** /api/users/users/ | 
[**Use-rsUsersBulkPartialUpdate**](UsersApi.md#Use-rsUsersBulkPartialUpdate) | **PATCH** /api/users/users/ | 
[**Use-rsUsersBulkUpdate**](UsersApi.md#Use-rsUsersBulkUpdate) | **PUT** /api/users/users/ | 
[**Use-rsUsersCreate**](UsersApi.md#Use-rsUsersCreate) | **POST** /api/users/users/ | 
[**Use-rsUsersDestroy**](UsersApi.md#Use-rsUsersDestroy) | **DELETE** /api/users/users/{id}/ | 
[**Use-rsUsersList**](UsersApi.md#Use-rsUsersList) | **GET** /api/users/users/ | 
[**Use-rsUsersPartialUpdate**](UsersApi.md#Use-rsUsersPartialUpdate) | **PATCH** /api/users/users/{id}/ | 
[**Use-rsUsersRetrieve**](UsersApi.md#Use-rsUsersRetrieve) | **GET** /api/users/users/{id}/ | 
[**Use-rsUsersUpdate**](UsersApi.md#Use-rsUsersUpdate) | **PUT** /api/users/users/{id}/ | 


<a id="Use-rsConfigRetrieve"></a>
# **Use-rsConfigRetrieve**
> System.Collections.Hashtable Use-rsConfigRetrieve<br>



An API endpoint via which a user can update his or her own UserConfig data (but no one else's).

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
    $Result = Use-rsConfigRetrieve
} catch {
    Write-Host ("Exception occurred when calling Use-rsConfigRetrieve: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
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

<a id="Use-rsGroupsBulkDestroy"></a>
# **Use-rsGroupsBulkDestroy**
> void Use-rsGroupsBulkDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-GroupRequest] <PSCustomObject[]><br>



Delete a list of group objects.

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

$GroupRequest = Initialize-GroupRequest -Name "MyName" # GroupRequest[] | 

try {
    $Result = Use-rsGroupsBulkDestroy -GroupRequest $GroupRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsGroupsBulkDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **GroupRequest** | [**GroupRequest[]**](GroupRequest.md)|  | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsGroupsBulkPartialUpdate"></a>
# **Use-rsGroupsBulkPartialUpdate**
> Group[] Use-rsGroupsBulkPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-GroupRequest] <PSCustomObject[]><br>



Patch a list of group objects.

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

$GroupRequest = Initialize-GroupRequest -Name "MyName" # GroupRequest[] | 

try {
    $Result = Use-rsGroupsBulkPartialUpdate -GroupRequest $GroupRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsGroupsBulkPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **GroupRequest** | [**GroupRequest[]**](GroupRequest.md)|  | 

### Return type

[**Group[]**](Group.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsGroupsBulkUpdate"></a>
# **Use-rsGroupsBulkUpdate**
> Group[] Use-rsGroupsBulkUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-GroupRequest] <PSCustomObject[]><br>



Put a list of group objects.

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

$GroupRequest = Initialize-GroupRequest -Name "MyName" # GroupRequest[] | 

try {
    $Result = Use-rsGroupsBulkUpdate -GroupRequest $GroupRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsGroupsBulkUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **GroupRequest** | [**GroupRequest[]**](GroupRequest.md)|  | 

### Return type

[**Group[]**](Group.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsGroupsCreate"></a>
# **Use-rsGroupsCreate**
> Group Use-rsGroupsCreate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-GroupRequest] <PSCustomObject><br>



Post a list of group objects.

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

$GroupRequest = Initialize-GroupRequest -Name "MyName" # GroupRequest | 

try {
    $Result = Use-rsGroupsCreate -GroupRequest $GroupRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsGroupsCreate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **GroupRequest** | [**GroupRequest**](GroupRequest.md)|  | 

### Return type

[**Group**](Group.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsGroupsDestroy"></a>
# **Use-rsGroupsDestroy**
> void Use-rsGroupsDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Delete a group object.

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

$Id = 56 # Int32 | A unique integer value identifying this group.

try {
    $Result = Use-rsGroupsDestroy -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Use-rsGroupsDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this group. | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsGroupsList"></a>
# **Use-rsGroupsList**
> PaginatedGroupList Use-rsGroupsList<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Limit] <System.Nullable[Int32]><br>
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
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Q] <String><br>



Get a list of group objects.

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

$Id = 0 # Int32[] |  (optional)
$IdEmpty = $true # Boolean |  (optional)
$IdGt = 0 # Int32[] |  (optional)
$IdGte = 0 # Int32[] |  (optional)
$IdLt = 0 # Int32[] |  (optional)
$IdLte = 0 # Int32[] |  (optional)
$IdN = 0 # Int32[] |  (optional)
$Limit = 56 # Int32 | Number of results to return per page. (optional)
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
$Q = "MyQ" # String | Search (optional)

try {
    $Result = Use-rsGroupsList -Id $Id -IdEmpty $IdEmpty -IdGt $IdGt -IdGte $IdGte -IdLt $IdLt -IdLte $IdLte -IdN $IdN -Limit $Limit -Name $Name -NameEmpty $NameEmpty -NameIc $NameIc -NameIe $NameIe -NameIew $NameIew -NameIsw $NameIsw -NameN $NameN -NameNic $NameNic -NameNie $NameNie -NameNiew $NameNiew -NameNisw $NameNisw -Offset $Offset -Ordering $Ordering -Q $Q
} catch {
    Write-Host ("Exception occurred when calling Use-rsGroupsList: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdEmpty** | **Boolean**|  | [optional] 
 **IdGt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdGte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdN** | [**Int32[]**](Int32.md)|  | [optional] 
 **Limit** | **Int32**| Number of results to return per page. | [optional] 
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
 **Q** | **String**| Search | [optional] 

### Return type

[**PaginatedGroupList**](PaginatedGroupList.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsGroupsPartialUpdate"></a>
# **Use-rsGroupsPartialUpdate**
> Group Use-rsGroupsPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PatchedGroupRequest] <PSCustomObject><br>



Patch a group object.

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

$Id = 56 # Int32 | A unique integer value identifying this group.
$PatchedGroupRequest = Initialize-PatchedGroupRequest -Name "MyName" # PatchedGroupRequest |  (optional)

try {
    $Result = Use-rsGroupsPartialUpdate -Id $Id -PatchedGroupRequest $PatchedGroupRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsGroupsPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this group. | 
 **PatchedGroupRequest** | [**PatchedGroupRequest**](PatchedGroupRequest.md)|  | [optional] 

### Return type

[**Group**](Group.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsGroupsRetrieve"></a>
# **Use-rsGroupsRetrieve**
> Group Use-rsGroupsRetrieve<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Get a group object.

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

$Id = 56 # Int32 | A unique integer value identifying this group.

try {
    $Result = Use-rsGroupsRetrieve -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Use-rsGroupsRetrieve: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this group. | 

### Return type

[**Group**](Group.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsGroupsUpdate"></a>
# **Use-rsGroupsUpdate**
> Group Use-rsGroupsUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-GroupRequest] <PSCustomObject><br>



Put a group object.

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

$Id = 56 # Int32 | A unique integer value identifying this group.
$GroupRequest = Initialize-GroupRequest -Name "MyName" # GroupRequest | 

try {
    $Result = Use-rsGroupsUpdate -Id $Id -GroupRequest $GroupRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsGroupsUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this group. | 
 **GroupRequest** | [**GroupRequest**](GroupRequest.md)|  | 

### Return type

[**Group**](Group.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsPermissionsBulkDestroy"></a>
# **Use-rsPermissionsBulkDestroy**
> void Use-rsPermissionsBulkDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ObjectPermissionRequest] <PSCustomObject[]><br>



Delete a list of permission objects.

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

$ObjectPermissionRequest = Initialize-ObjectPermissionRequest -Name "MyName" -Description "MyDescription" -Enabled $false -ObjectTypes "MyObjectTypes" -Groups 0 -Users 0 -Actions "MyActions" -Constraints # ObjectPermissionRequest[] | 

try {
    $Result = Use-rsPermissionsBulkDestroy -ObjectPermissionRequest $ObjectPermissionRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsPermissionsBulkDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ObjectPermissionRequest** | [**ObjectPermissionRequest[]**](ObjectPermissionRequest.md)|  | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsPermissionsBulkPartialUpdate"></a>
# **Use-rsPermissionsBulkPartialUpdate**
> ObjectPermission[] Use-rsPermissionsBulkPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ObjectPermissionRequest] <PSCustomObject[]><br>



Patch a list of permission objects.

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

$ObjectPermissionRequest = Initialize-ObjectPermissionRequest -Name "MyName" -Description "MyDescription" -Enabled $false -ObjectTypes "MyObjectTypes" -Groups 0 -Users 0 -Actions "MyActions" -Constraints # ObjectPermissionRequest[] | 

try {
    $Result = Use-rsPermissionsBulkPartialUpdate -ObjectPermissionRequest $ObjectPermissionRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsPermissionsBulkPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ObjectPermissionRequest** | [**ObjectPermissionRequest[]**](ObjectPermissionRequest.md)|  | 

### Return type

[**ObjectPermission[]**](ObjectPermission.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsPermissionsBulkUpdate"></a>
# **Use-rsPermissionsBulkUpdate**
> ObjectPermission[] Use-rsPermissionsBulkUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ObjectPermissionRequest] <PSCustomObject[]><br>



Put a list of permission objects.

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

$ObjectPermissionRequest = Initialize-ObjectPermissionRequest -Name "MyName" -Description "MyDescription" -Enabled $false -ObjectTypes "MyObjectTypes" -Groups 0 -Users 0 -Actions "MyActions" -Constraints # ObjectPermissionRequest[] | 

try {
    $Result = Use-rsPermissionsBulkUpdate -ObjectPermissionRequest $ObjectPermissionRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsPermissionsBulkUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ObjectPermissionRequest** | [**ObjectPermissionRequest[]**](ObjectPermissionRequest.md)|  | 

### Return type

[**ObjectPermission[]**](ObjectPermission.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsPermissionsCreate"></a>
# **Use-rsPermissionsCreate**
> ObjectPermission Use-rsPermissionsCreate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableObjectPermissionRequest] <PSCustomObject><br>



Post a list of permission objects.

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

$WritableObjectPermissionRequest = Initialize-WritableObjectPermissionRequest -Name "MyName" -Description "MyDescription" -Enabled $false -ObjectTypes "MyObjectTypes" -Groups 0 -Users 0 -Actions "MyActions" -Constraints # WritableObjectPermissionRequest | 

try {
    $Result = Use-rsPermissionsCreate -WritableObjectPermissionRequest $WritableObjectPermissionRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsPermissionsCreate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WritableObjectPermissionRequest** | [**WritableObjectPermissionRequest**](WritableObjectPermissionRequest.md)|  | 

### Return type

[**ObjectPermission**](ObjectPermission.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsPermissionsDestroy"></a>
# **Use-rsPermissionsDestroy**
> void Use-rsPermissionsDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Delete a permission object.

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

$Id = 56 # Int32 | A unique integer value identifying this permission.

try {
    $Result = Use-rsPermissionsDestroy -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Use-rsPermissionsDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this permission. | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsPermissionsList"></a>
# **Use-rsPermissionsList**
> PaginatedObjectPermissionList Use-rsPermissionsList<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CanAdd] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CanChange] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CanDelete] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CanView] <System.Nullable[Boolean]><br>
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
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Enabled] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Group] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-GroupN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-GroupId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-GroupIdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Limit] <System.Nullable[Int32]><br>
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
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ObjectTypes] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ObjectTypesN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Offset] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Ordering] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Q] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-User] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UserN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UserId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UserIdN] <System.Nullable[Int32][]><br>



Get a list of permission objects.

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

$CanAdd = $true # Boolean |  (optional)
$CanChange = $true # Boolean |  (optional)
$CanDelete = $true # Boolean |  (optional)
$CanView = $true # Boolean |  (optional)
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
$Enabled = $true # Boolean |  (optional)
$Group = "MyGroup" # String[] | Group (name) (optional)
$GroupN = "MyGroupN" # String[] | Group (name) (optional)
$GroupId = 0 # Int32[] | Group (optional)
$GroupIdN = 0 # Int32[] | Group (optional)
$Id = 0 # Int32[] |  (optional)
$IdEmpty = $true # Boolean |  (optional)
$IdGt = 0 # Int32[] |  (optional)
$IdGte = 0 # Int32[] |  (optional)
$IdLt = 0 # Int32[] |  (optional)
$IdLte = 0 # Int32[] |  (optional)
$IdN = 0 # Int32[] |  (optional)
$Limit = 56 # Int32 | Number of results to return per page. (optional)
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
$ObjectTypes = 0 # Int32[] |  (optional)
$ObjectTypesN = 0 # Int32[] |  (optional)
$Offset = 56 # Int32 | The initial index from which to return the results. (optional)
$Ordering = "MyOrdering" # String | Which field to use when ordering the results. (optional)
$Q = "MyQ" # String | Search (optional)
$User = "MyUser" # String[] | User (name) (optional)
$UserN = "MyUserN" # String[] | User (name) (optional)
$UserId = 0 # Int32[] | User (optional)
$UserIdN = 0 # Int32[] | User (optional)

try {
    $Result = Use-rsPermissionsList -CanAdd $CanAdd -CanChange $CanChange -CanDelete $CanDelete -CanView $CanView -Description $Description -DescriptionEmpty $DescriptionEmpty -DescriptionIc $DescriptionIc -DescriptionIe $DescriptionIe -DescriptionIew $DescriptionIew -DescriptionIsw $DescriptionIsw -DescriptionN $DescriptionN -DescriptionNic $DescriptionNic -DescriptionNie $DescriptionNie -DescriptionNiew $DescriptionNiew -DescriptionNisw $DescriptionNisw -Enabled $Enabled -Group $Group -GroupN $GroupN -GroupId $GroupId -GroupIdN $GroupIdN -Id $Id -IdEmpty $IdEmpty -IdGt $IdGt -IdGte $IdGte -IdLt $IdLt -IdLte $IdLte -IdN $IdN -Limit $Limit -Name $Name -NameEmpty $NameEmpty -NameIc $NameIc -NameIe $NameIe -NameIew $NameIew -NameIsw $NameIsw -NameN $NameN -NameNic $NameNic -NameNie $NameNie -NameNiew $NameNiew -NameNisw $NameNisw -ObjectTypes $ObjectTypes -ObjectTypesN $ObjectTypesN -Offset $Offset -Ordering $Ordering -Q $Q -User $User -UserN $UserN -UserId $UserId -UserIdN $UserIdN
} catch {
    Write-Host ("Exception occurred when calling Use-rsPermissionsList: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **CanAdd** | **Boolean**|  | [optional] 
 **CanChange** | **Boolean**|  | [optional] 
 **CanDelete** | **Boolean**|  | [optional] 
 **CanView** | **Boolean**|  | [optional] 
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
 **Enabled** | **Boolean**|  | [optional] 
 **Group** | [**String[]**](String.md)| Group (name) | [optional] 
 **GroupN** | [**String[]**](String.md)| Group (name) | [optional] 
 **GroupId** | [**Int32[]**](Int32.md)| Group | [optional] 
 **GroupIdN** | [**Int32[]**](Int32.md)| Group | [optional] 
 **Id** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdEmpty** | **Boolean**|  | [optional] 
 **IdGt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdGte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdN** | [**Int32[]**](Int32.md)|  | [optional] 
 **Limit** | **Int32**| Number of results to return per page. | [optional] 
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
 **ObjectTypes** | [**Int32[]**](Int32.md)|  | [optional] 
 **ObjectTypesN** | [**Int32[]**](Int32.md)|  | [optional] 
 **Offset** | **Int32**| The initial index from which to return the results. | [optional] 
 **Ordering** | **String**| Which field to use when ordering the results. | [optional] 
 **Q** | **String**| Search | [optional] 
 **User** | [**String[]**](String.md)| User (name) | [optional] 
 **UserN** | [**String[]**](String.md)| User (name) | [optional] 
 **UserId** | [**Int32[]**](Int32.md)| User | [optional] 
 **UserIdN** | [**Int32[]**](Int32.md)| User | [optional] 

### Return type

[**PaginatedObjectPermissionList**](PaginatedObjectPermissionList.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsPermissionsPartialUpdate"></a>
# **Use-rsPermissionsPartialUpdate**
> ObjectPermission Use-rsPermissionsPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PatchedWritableObjectPermissionRequest] <PSCustomObject><br>



Patch a permission object.

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

$Id = 56 # Int32 | A unique integer value identifying this permission.
$PatchedWritableObjectPermissionRequest = Initialize-PatchedWritableObjectPermissionRequest -Name "MyName" -Description "MyDescription" -Enabled $false -ObjectTypes "MyObjectTypes" -Groups 0 -Users 0 -Actions "MyActions" -Constraints # PatchedWritableObjectPermissionRequest |  (optional)

try {
    $Result = Use-rsPermissionsPartialUpdate -Id $Id -PatchedWritableObjectPermissionRequest $PatchedWritableObjectPermissionRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsPermissionsPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this permission. | 
 **PatchedWritableObjectPermissionRequest** | [**PatchedWritableObjectPermissionRequest**](PatchedWritableObjectPermissionRequest.md)|  | [optional] 

### Return type

[**ObjectPermission**](ObjectPermission.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsPermissionsRetrieve"></a>
# **Use-rsPermissionsRetrieve**
> ObjectPermission Use-rsPermissionsRetrieve<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Get a permission object.

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

$Id = 56 # Int32 | A unique integer value identifying this permission.

try {
    $Result = Use-rsPermissionsRetrieve -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Use-rsPermissionsRetrieve: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this permission. | 

### Return type

[**ObjectPermission**](ObjectPermission.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsPermissionsUpdate"></a>
# **Use-rsPermissionsUpdate**
> ObjectPermission Use-rsPermissionsUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableObjectPermissionRequest] <PSCustomObject><br>



Put a permission object.

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

$Id = 56 # Int32 | A unique integer value identifying this permission.
$WritableObjectPermissionRequest = Initialize-WritableObjectPermissionRequest -Name "MyName" -Description "MyDescription" -Enabled $false -ObjectTypes "MyObjectTypes" -Groups 0 -Users 0 -Actions "MyActions" -Constraints # WritableObjectPermissionRequest | 

try {
    $Result = Use-rsPermissionsUpdate -Id $Id -WritableObjectPermissionRequest $WritableObjectPermissionRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsPermissionsUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this permission. | 
 **WritableObjectPermissionRequest** | [**WritableObjectPermissionRequest**](WritableObjectPermissionRequest.md)|  | 

### Return type

[**ObjectPermission**](ObjectPermission.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsTokensBulkDestroy"></a>
# **Use-rsTokensBulkDestroy**
> void Use-rsTokensBulkDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TokenRequest] <PSCustomObject[]><br>



Delete a list of token objects.

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

$NestedUserRequest = Initialize-NestedUserRequest -Username "MyUsername"
$TokenRequest = Initialize-TokenRequest -User $NestedUserRequest -Expires (Get-Date) -LastUsed (Get-Date) -Key "MyKey" -WriteEnabled $false -Description "MyDescription" # TokenRequest[] | 

try {
    $Result = Use-rsTokensBulkDestroy -TokenRequest $TokenRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsTokensBulkDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **TokenRequest** | [**TokenRequest[]**](TokenRequest.md)|  | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsTokensBulkPartialUpdate"></a>
# **Use-rsTokensBulkPartialUpdate**
> Token[] Use-rsTokensBulkPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TokenRequest] <PSCustomObject[]><br>



Patch a list of token objects.

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

$NestedUserRequest = Initialize-NestedUserRequest -Username "MyUsername"
$TokenRequest = Initialize-TokenRequest -User $NestedUserRequest -Expires (Get-Date) -LastUsed (Get-Date) -Key "MyKey" -WriteEnabled $false -Description "MyDescription" # TokenRequest[] | 

try {
    $Result = Use-rsTokensBulkPartialUpdate -TokenRequest $TokenRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsTokensBulkPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **TokenRequest** | [**TokenRequest[]**](TokenRequest.md)|  | 

### Return type

[**Token[]**](Token.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsTokensBulkUpdate"></a>
# **Use-rsTokensBulkUpdate**
> Token[] Use-rsTokensBulkUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TokenRequest] <PSCustomObject[]><br>



Put a list of token objects.

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

$NestedUserRequest = Initialize-NestedUserRequest -Username "MyUsername"
$TokenRequest = Initialize-TokenRequest -User $NestedUserRequest -Expires (Get-Date) -LastUsed (Get-Date) -Key "MyKey" -WriteEnabled $false -Description "MyDescription" # TokenRequest[] | 

try {
    $Result = Use-rsTokensBulkUpdate -TokenRequest $TokenRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsTokensBulkUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **TokenRequest** | [**TokenRequest[]**](TokenRequest.md)|  | 

### Return type

[**Token[]**](Token.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsTokensCreate"></a>
# **Use-rsTokensCreate**
> Token Use-rsTokensCreate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableTokenRequest] <PSCustomObject><br>



Post a list of token objects.

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

$WritableTokenRequest = Initialize-WritableTokenRequest -User 0 -Expires (Get-Date) -LastUsed (Get-Date) -Key "MyKey" -WriteEnabled $false -Description "MyDescription" # WritableTokenRequest | 

try {
    $Result = Use-rsTokensCreate -WritableTokenRequest $WritableTokenRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsTokensCreate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WritableTokenRequest** | [**WritableTokenRequest**](WritableTokenRequest.md)|  | 

### Return type

[**Token**](Token.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsTokensDestroy"></a>
# **Use-rsTokensDestroy**
> void Use-rsTokensDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Delete a token object.

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

$Id = 56 # Int32 | A unique integer value identifying this token.

try {
    $Result = Use-rsTokensDestroy -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Use-rsTokensDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this token. | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsTokensList"></a>
# **Use-rsTokensList**
> PaginatedTokenList Use-rsTokensList<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Created] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedGte] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedLte] <System.Nullable[System.DateTime]><br>
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
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Expires] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ExpiresGte] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ExpiresLte] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Key] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-KeyEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-KeyIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-KeyIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-KeyIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-KeyIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-KeyN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-KeyNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-KeyNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-KeyNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-KeyNisw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Limit] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Offset] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Ordering] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Q] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-User] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UserN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UserId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UserIdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WriteEnabled] <System.Nullable[Boolean]><br>



Get a list of token objects.

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

$Created = (Get-Date) # System.DateTime |  (optional)
$CreatedGte = (Get-Date) # System.DateTime |  (optional)
$CreatedLte = (Get-Date) # System.DateTime |  (optional)
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
$Expires = (Get-Date) # System.DateTime |  (optional)
$ExpiresGte = (Get-Date) # System.DateTime |  (optional)
$ExpiresLte = (Get-Date) # System.DateTime |  (optional)
$Id = 0 # Int32[] |  (optional)
$IdEmpty = $true # Boolean |  (optional)
$IdGt = 0 # Int32[] |  (optional)
$IdGte = 0 # Int32[] |  (optional)
$IdLt = 0 # Int32[] |  (optional)
$IdLte = 0 # Int32[] |  (optional)
$IdN = 0 # Int32[] |  (optional)
$Key = "MyKey" # String[] |  (optional)
$KeyEmpty = $true # Boolean |  (optional)
$KeyIc = "MyKeyIc" # String[] |  (optional)
$KeyIe = "MyKeyIe" # String[] |  (optional)
$KeyIew = "MyKeyIew" # String[] |  (optional)
$KeyIsw = "MyKeyIsw" # String[] |  (optional)
$KeyN = "MyKeyN" # String[] |  (optional)
$KeyNic = "MyKeyNic" # String[] |  (optional)
$KeyNie = "MyKeyNie" # String[] |  (optional)
$KeyNiew = "MyKeyNiew" # String[] |  (optional)
$KeyNisw = "MyKeyNisw" # String[] |  (optional)
$Limit = 56 # Int32 | Number of results to return per page. (optional)
$Offset = 56 # Int32 | The initial index from which to return the results. (optional)
$Ordering = "MyOrdering" # String | Which field to use when ordering the results. (optional)
$Q = "MyQ" # String | Search (optional)
$User = "MyUser" # String[] | User (name) (optional)
$UserN = "MyUserN" # String[] | User (name) (optional)
$UserId = 0 # Int32[] | User (optional)
$UserIdN = 0 # Int32[] | User (optional)
$WriteEnabled = $true # Boolean |  (optional)

try {
    $Result = Use-rsTokensList -Created $Created -CreatedGte $CreatedGte -CreatedLte $CreatedLte -Description $Description -DescriptionEmpty $DescriptionEmpty -DescriptionIc $DescriptionIc -DescriptionIe $DescriptionIe -DescriptionIew $DescriptionIew -DescriptionIsw $DescriptionIsw -DescriptionN $DescriptionN -DescriptionNic $DescriptionNic -DescriptionNie $DescriptionNie -DescriptionNiew $DescriptionNiew -DescriptionNisw $DescriptionNisw -Expires $Expires -ExpiresGte $ExpiresGte -ExpiresLte $ExpiresLte -Id $Id -IdEmpty $IdEmpty -IdGt $IdGt -IdGte $IdGte -IdLt $IdLt -IdLte $IdLte -IdN $IdN -Key $Key -KeyEmpty $KeyEmpty -KeyIc $KeyIc -KeyIe $KeyIe -KeyIew $KeyIew -KeyIsw $KeyIsw -KeyN $KeyN -KeyNic $KeyNic -KeyNie $KeyNie -KeyNiew $KeyNiew -KeyNisw $KeyNisw -Limit $Limit -Offset $Offset -Ordering $Ordering -Q $Q -User $User -UserN $UserN -UserId $UserId -UserIdN $UserIdN -WriteEnabled $WriteEnabled
} catch {
    Write-Host ("Exception occurred when calling Use-rsTokensList: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Created** | **System.DateTime**|  | [optional] 
 **CreatedGte** | **System.DateTime**|  | [optional] 
 **CreatedLte** | **System.DateTime**|  | [optional] 
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
 **Expires** | **System.DateTime**|  | [optional] 
 **ExpiresGte** | **System.DateTime**|  | [optional] 
 **ExpiresLte** | **System.DateTime**|  | [optional] 
 **Id** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdEmpty** | **Boolean**|  | [optional] 
 **IdGt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdGte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdN** | [**Int32[]**](Int32.md)|  | [optional] 
 **Key** | [**String[]**](String.md)|  | [optional] 
 **KeyEmpty** | **Boolean**|  | [optional] 
 **KeyIc** | [**String[]**](String.md)|  | [optional] 
 **KeyIe** | [**String[]**](String.md)|  | [optional] 
 **KeyIew** | [**String[]**](String.md)|  | [optional] 
 **KeyIsw** | [**String[]**](String.md)|  | [optional] 
 **KeyN** | [**String[]**](String.md)|  | [optional] 
 **KeyNic** | [**String[]**](String.md)|  | [optional] 
 **KeyNie** | [**String[]**](String.md)|  | [optional] 
 **KeyNiew** | [**String[]**](String.md)|  | [optional] 
 **KeyNisw** | [**String[]**](String.md)|  | [optional] 
 **Limit** | **Int32**| Number of results to return per page. | [optional] 
 **Offset** | **Int32**| The initial index from which to return the results. | [optional] 
 **Ordering** | **String**| Which field to use when ordering the results. | [optional] 
 **Q** | **String**| Search | [optional] 
 **User** | [**String[]**](String.md)| User (name) | [optional] 
 **UserN** | [**String[]**](String.md)| User (name) | [optional] 
 **UserId** | [**Int32[]**](Int32.md)| User | [optional] 
 **UserIdN** | [**Int32[]**](Int32.md)| User | [optional] 
 **WriteEnabled** | **Boolean**|  | [optional] 

### Return type

[**PaginatedTokenList**](PaginatedTokenList.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsTokensPartialUpdate"></a>
# **Use-rsTokensPartialUpdate**
> Token Use-rsTokensPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PatchedWritableTokenRequest] <PSCustomObject><br>



Patch a token object.

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

$Id = 56 # Int32 | A unique integer value identifying this token.
$PatchedWritableTokenRequest = Initialize-PatchedWritableTokenRequest -User 0 -Expires (Get-Date) -LastUsed (Get-Date) -Key "MyKey" -WriteEnabled $false -Description "MyDescription" # PatchedWritableTokenRequest |  (optional)

try {
    $Result = Use-rsTokensPartialUpdate -Id $Id -PatchedWritableTokenRequest $PatchedWritableTokenRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsTokensPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this token. | 
 **PatchedWritableTokenRequest** | [**PatchedWritableTokenRequest**](PatchedWritableTokenRequest.md)|  | [optional] 

### Return type

[**Token**](Token.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsTokensProvisionCreate"></a>
# **Use-rsTokensProvisionCreate**
> TokenProvision Use-rsTokensProvisionCreate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TokenProvisionRequest] <PSCustomObject><br>



Non-authenticated REST API endpoint via which a user may create a Token.

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

$TokenProvisionRequest = Initialize-TokenProvisionRequest -Expires (Get-Date) -WriteEnabled $false -Description "MyDescription" -Username "MyUsername" -Password "MyPassword" # TokenProvisionRequest | 

try {
    $Result = Use-rsTokensProvisionCreate -TokenProvisionRequest $TokenProvisionRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsTokensProvisionCreate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **TokenProvisionRequest** | [**TokenProvisionRequest**](TokenProvisionRequest.md)|  | 

### Return type

[**TokenProvision**](TokenProvision.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsTokensRetrieve"></a>
# **Use-rsTokensRetrieve**
> Token Use-rsTokensRetrieve<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Get a token object.

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

$Id = 56 # Int32 | A unique integer value identifying this token.

try {
    $Result = Use-rsTokensRetrieve -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Use-rsTokensRetrieve: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this token. | 

### Return type

[**Token**](Token.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsTokensUpdate"></a>
# **Use-rsTokensUpdate**
> Token Use-rsTokensUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableTokenRequest] <PSCustomObject><br>



Put a token object.

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

$Id = 56 # Int32 | A unique integer value identifying this token.
$WritableTokenRequest = Initialize-WritableTokenRequest -User 0 -Expires (Get-Date) -LastUsed (Get-Date) -Key "MyKey" -WriteEnabled $false -Description "MyDescription" # WritableTokenRequest | 

try {
    $Result = Use-rsTokensUpdate -Id $Id -WritableTokenRequest $WritableTokenRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsTokensUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this token. | 
 **WritableTokenRequest** | [**WritableTokenRequest**](WritableTokenRequest.md)|  | 

### Return type

[**Token**](Token.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsUsersBulkDestroy"></a>
# **Use-rsUsersBulkDestroy**
> void Use-rsUsersBulkDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UserRequest] <PSCustomObject[]><br>



Delete a list of user objects.

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

$UserRequest = Initialize-UserRequest -Username "MyUsername" -Password "MyPassword" -FirstName "MyFirstName" -LastName "MyLastName" -Email "MyEmail" -IsStaff $false -IsActive $false -DateJoined (Get-Date) -LastLogin (Get-Date) -Groups 0 # UserRequest[] | 

try {
    $Result = Use-rsUsersBulkDestroy -UserRequest $UserRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsUsersBulkDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **UserRequest** | [**UserRequest[]**](UserRequest.md)|  | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsUsersBulkPartialUpdate"></a>
# **Use-rsUsersBulkPartialUpdate**
> User[] Use-rsUsersBulkPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UserRequest] <PSCustomObject[]><br>



Patch a list of user objects.

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

$UserRequest = Initialize-UserRequest -Username "MyUsername" -Password "MyPassword" -FirstName "MyFirstName" -LastName "MyLastName" -Email "MyEmail" -IsStaff $false -IsActive $false -DateJoined (Get-Date) -LastLogin (Get-Date) -Groups 0 # UserRequest[] | 

try {
    $Result = Use-rsUsersBulkPartialUpdate -UserRequest $UserRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsUsersBulkPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **UserRequest** | [**UserRequest[]**](UserRequest.md)|  | 

### Return type

[**User[]**](User.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsUsersBulkUpdate"></a>
# **Use-rsUsersBulkUpdate**
> User[] Use-rsUsersBulkUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UserRequest] <PSCustomObject[]><br>



Put a list of user objects.

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

$UserRequest = Initialize-UserRequest -Username "MyUsername" -Password "MyPassword" -FirstName "MyFirstName" -LastName "MyLastName" -Email "MyEmail" -IsStaff $false -IsActive $false -DateJoined (Get-Date) -LastLogin (Get-Date) -Groups 0 # UserRequest[] | 

try {
    $Result = Use-rsUsersBulkUpdate -UserRequest $UserRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsUsersBulkUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **UserRequest** | [**UserRequest[]**](UserRequest.md)|  | 

### Return type

[**User[]**](User.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsUsersCreate"></a>
# **Use-rsUsersCreate**
> User Use-rsUsersCreate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableUserRequest] <PSCustomObject><br>



Post a list of user objects.

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

$WritableUserRequest = Initialize-WritableUserRequest -Username "MyUsername" -Password "MyPassword" -FirstName "MyFirstName" -LastName "MyLastName" -Email "MyEmail" -IsStaff $false -IsActive $false -DateJoined (Get-Date) -LastLogin (Get-Date) -Groups 0 # WritableUserRequest | 

try {
    $Result = Use-rsUsersCreate -WritableUserRequest $WritableUserRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsUsersCreate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WritableUserRequest** | [**WritableUserRequest**](WritableUserRequest.md)|  | 

### Return type

[**User**](User.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsUsersDestroy"></a>
# **Use-rsUsersDestroy**
> void Use-rsUsersDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Delete a user object.

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

$Id = 56 # Int32 | A unique integer value identifying this user.

try {
    $Result = Use-rsUsersDestroy -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Use-rsUsersDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this user. | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsUsersList"></a>
# **Use-rsUsersList**
> PaginatedUserList Use-rsUsersList<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Email] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-EmailEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-EmailIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-EmailIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-EmailIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-EmailIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-EmailN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-EmailNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-EmailNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-EmailNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-EmailNisw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-FirstName] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-FirstNameEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-FirstNameIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-FirstNameIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-FirstNameIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-FirstNameIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-FirstNameN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-FirstNameNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-FirstNameNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-FirstNameNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-FirstNameNisw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Group] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-GroupN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-GroupId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-GroupIdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IsActive] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IsStaff] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IsSuperuser] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastName] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastNameEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastNameIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastNameIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastNameIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastNameIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastNameN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastNameNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastNameNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastNameNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-LastNameNisw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Limit] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Offset] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Ordering] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Q] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Username] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UsernameEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UsernameIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UsernameIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UsernameIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UsernameIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UsernameN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UsernameNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UsernameNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UsernameNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UsernameNisw] <String[]><br>



Get a list of user objects.

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

$Email = "MyEmail" # String[] |  (optional)
$EmailEmpty = $true # Boolean |  (optional)
$EmailIc = "MyEmailIc" # String[] |  (optional)
$EmailIe = "MyEmailIe" # String[] |  (optional)
$EmailIew = "MyEmailIew" # String[] |  (optional)
$EmailIsw = "MyEmailIsw" # String[] |  (optional)
$EmailN = "MyEmailN" # String[] |  (optional)
$EmailNic = "MyEmailNic" # String[] |  (optional)
$EmailNie = "MyEmailNie" # String[] |  (optional)
$EmailNiew = "MyEmailNiew" # String[] |  (optional)
$EmailNisw = "MyEmailNisw" # String[] |  (optional)
$FirstName = "MyFirstName" # String[] |  (optional)
$FirstNameEmpty = $true # Boolean |  (optional)
$FirstNameIc = "MyFirstNameIc" # String[] |  (optional)
$FirstNameIe = "MyFirstNameIe" # String[] |  (optional)
$FirstNameIew = "MyFirstNameIew" # String[] |  (optional)
$FirstNameIsw = "MyFirstNameIsw" # String[] |  (optional)
$FirstNameN = "MyFirstNameN" # String[] |  (optional)
$FirstNameNic = "MyFirstNameNic" # String[] |  (optional)
$FirstNameNie = "MyFirstNameNie" # String[] |  (optional)
$FirstNameNiew = "MyFirstNameNiew" # String[] |  (optional)
$FirstNameNisw = "MyFirstNameNisw" # String[] |  (optional)
$Group = "MyGroup" # String[] | Group (name) (optional)
$GroupN = "MyGroupN" # String[] | Group (name) (optional)
$GroupId = 0 # Int32[] | Group (optional)
$GroupIdN = 0 # Int32[] | Group (optional)
$Id = 0 # Int32[] |  (optional)
$IdEmpty = $true # Boolean |  (optional)
$IdGt = 0 # Int32[] |  (optional)
$IdGte = 0 # Int32[] |  (optional)
$IdLt = 0 # Int32[] |  (optional)
$IdLte = 0 # Int32[] |  (optional)
$IdN = 0 # Int32[] |  (optional)
$IsActive = $true # Boolean |  (optional)
$IsStaff = $true # Boolean |  (optional)
$IsSuperuser = $true # Boolean |  (optional)
$LastName = "MyLastName" # String[] |  (optional)
$LastNameEmpty = $true # Boolean |  (optional)
$LastNameIc = "MyLastNameIc" # String[] |  (optional)
$LastNameIe = "MyLastNameIe" # String[] |  (optional)
$LastNameIew = "MyLastNameIew" # String[] |  (optional)
$LastNameIsw = "MyLastNameIsw" # String[] |  (optional)
$LastNameN = "MyLastNameN" # String[] |  (optional)
$LastNameNic = "MyLastNameNic" # String[] |  (optional)
$LastNameNie = "MyLastNameNie" # String[] |  (optional)
$LastNameNiew = "MyLastNameNiew" # String[] |  (optional)
$LastNameNisw = "MyLastNameNisw" # String[] |  (optional)
$Limit = 56 # Int32 | Number of results to return per page. (optional)
$Offset = 56 # Int32 | The initial index from which to return the results. (optional)
$Ordering = "MyOrdering" # String | Which field to use when ordering the results. (optional)
$Q = "MyQ" # String | Search (optional)
$Username = "MyUsername" # String[] |  (optional)
$UsernameEmpty = $true # Boolean |  (optional)
$UsernameIc = "MyUsernameIc" # String[] |  (optional)
$UsernameIe = "MyUsernameIe" # String[] |  (optional)
$UsernameIew = "MyUsernameIew" # String[] |  (optional)
$UsernameIsw = "MyUsernameIsw" # String[] |  (optional)
$UsernameN = "MyUsernameN" # String[] |  (optional)
$UsernameNic = "MyUsernameNic" # String[] |  (optional)
$UsernameNie = "MyUsernameNie" # String[] |  (optional)
$UsernameNiew = "MyUsernameNiew" # String[] |  (optional)
$UsernameNisw = "MyUsernameNisw" # String[] |  (optional)

try {
    $Result = Use-rsUsersList -Email $Email -EmailEmpty $EmailEmpty -EmailIc $EmailIc -EmailIe $EmailIe -EmailIew $EmailIew -EmailIsw $EmailIsw -EmailN $EmailN -EmailNic $EmailNic -EmailNie $EmailNie -EmailNiew $EmailNiew -EmailNisw $EmailNisw -FirstName $FirstName -FirstNameEmpty $FirstNameEmpty -FirstNameIc $FirstNameIc -FirstNameIe $FirstNameIe -FirstNameIew $FirstNameIew -FirstNameIsw $FirstNameIsw -FirstNameN $FirstNameN -FirstNameNic $FirstNameNic -FirstNameNie $FirstNameNie -FirstNameNiew $FirstNameNiew -FirstNameNisw $FirstNameNisw -Group $Group -GroupN $GroupN -GroupId $GroupId -GroupIdN $GroupIdN -Id $Id -IdEmpty $IdEmpty -IdGt $IdGt -IdGte $IdGte -IdLt $IdLt -IdLte $IdLte -IdN $IdN -IsActive $IsActive -IsStaff $IsStaff -IsSuperuser $IsSuperuser -LastName $LastName -LastNameEmpty $LastNameEmpty -LastNameIc $LastNameIc -LastNameIe $LastNameIe -LastNameIew $LastNameIew -LastNameIsw $LastNameIsw -LastNameN $LastNameN -LastNameNic $LastNameNic -LastNameNie $LastNameNie -LastNameNiew $LastNameNiew -LastNameNisw $LastNameNisw -Limit $Limit -Offset $Offset -Ordering $Ordering -Q $Q -Username $Username -UsernameEmpty $UsernameEmpty -UsernameIc $UsernameIc -UsernameIe $UsernameIe -UsernameIew $UsernameIew -UsernameIsw $UsernameIsw -UsernameN $UsernameN -UsernameNic $UsernameNic -UsernameNie $UsernameNie -UsernameNiew $UsernameNiew -UsernameNisw $UsernameNisw
} catch {
    Write-Host ("Exception occurred when calling Use-rsUsersList: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Email** | [**String[]**](String.md)|  | [optional] 
 **EmailEmpty** | **Boolean**|  | [optional] 
 **EmailIc** | [**String[]**](String.md)|  | [optional] 
 **EmailIe** | [**String[]**](String.md)|  | [optional] 
 **EmailIew** | [**String[]**](String.md)|  | [optional] 
 **EmailIsw** | [**String[]**](String.md)|  | [optional] 
 **EmailN** | [**String[]**](String.md)|  | [optional] 
 **EmailNic** | [**String[]**](String.md)|  | [optional] 
 **EmailNie** | [**String[]**](String.md)|  | [optional] 
 **EmailNiew** | [**String[]**](String.md)|  | [optional] 
 **EmailNisw** | [**String[]**](String.md)|  | [optional] 
 **FirstName** | [**String[]**](String.md)|  | [optional] 
 **FirstNameEmpty** | **Boolean**|  | [optional] 
 **FirstNameIc** | [**String[]**](String.md)|  | [optional] 
 **FirstNameIe** | [**String[]**](String.md)|  | [optional] 
 **FirstNameIew** | [**String[]**](String.md)|  | [optional] 
 **FirstNameIsw** | [**String[]**](String.md)|  | [optional] 
 **FirstNameN** | [**String[]**](String.md)|  | [optional] 
 **FirstNameNic** | [**String[]**](String.md)|  | [optional] 
 **FirstNameNie** | [**String[]**](String.md)|  | [optional] 
 **FirstNameNiew** | [**String[]**](String.md)|  | [optional] 
 **FirstNameNisw** | [**String[]**](String.md)|  | [optional] 
 **Group** | [**String[]**](String.md)| Group (name) | [optional] 
 **GroupN** | [**String[]**](String.md)| Group (name) | [optional] 
 **GroupId** | [**Int32[]**](Int32.md)| Group | [optional] 
 **GroupIdN** | [**Int32[]**](Int32.md)| Group | [optional] 
 **Id** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdEmpty** | **Boolean**|  | [optional] 
 **IdGt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdGte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdN** | [**Int32[]**](Int32.md)|  | [optional] 
 **IsActive** | **Boolean**|  | [optional] 
 **IsStaff** | **Boolean**|  | [optional] 
 **IsSuperuser** | **Boolean**|  | [optional] 
 **LastName** | [**String[]**](String.md)|  | [optional] 
 **LastNameEmpty** | **Boolean**|  | [optional] 
 **LastNameIc** | [**String[]**](String.md)|  | [optional] 
 **LastNameIe** | [**String[]**](String.md)|  | [optional] 
 **LastNameIew** | [**String[]**](String.md)|  | [optional] 
 **LastNameIsw** | [**String[]**](String.md)|  | [optional] 
 **LastNameN** | [**String[]**](String.md)|  | [optional] 
 **LastNameNic** | [**String[]**](String.md)|  | [optional] 
 **LastNameNie** | [**String[]**](String.md)|  | [optional] 
 **LastNameNiew** | [**String[]**](String.md)|  | [optional] 
 **LastNameNisw** | [**String[]**](String.md)|  | [optional] 
 **Limit** | **Int32**| Number of results to return per page. | [optional] 
 **Offset** | **Int32**| The initial index from which to return the results. | [optional] 
 **Ordering** | **String**| Which field to use when ordering the results. | [optional] 
 **Q** | **String**| Search | [optional] 
 **Username** | [**String[]**](String.md)|  | [optional] 
 **UsernameEmpty** | **Boolean**|  | [optional] 
 **UsernameIc** | [**String[]**](String.md)|  | [optional] 
 **UsernameIe** | [**String[]**](String.md)|  | [optional] 
 **UsernameIew** | [**String[]**](String.md)|  | [optional] 
 **UsernameIsw** | [**String[]**](String.md)|  | [optional] 
 **UsernameN** | [**String[]**](String.md)|  | [optional] 
 **UsernameNic** | [**String[]**](String.md)|  | [optional] 
 **UsernameNie** | [**String[]**](String.md)|  | [optional] 
 **UsernameNiew** | [**String[]**](String.md)|  | [optional] 
 **UsernameNisw** | [**String[]**](String.md)|  | [optional] 

### Return type

[**PaginatedUserList**](PaginatedUserList.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsUsersPartialUpdate"></a>
# **Use-rsUsersPartialUpdate**
> User Use-rsUsersPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PatchedWritableUserRequest] <PSCustomObject><br>



Patch a user object.

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

$Id = 56 # Int32 | A unique integer value identifying this user.
$PatchedWritableUserRequest = Initialize-PatchedWritableUserRequest -Username "MyUsername" -Password "MyPassword" -FirstName "MyFirstName" -LastName "MyLastName" -Email "MyEmail" -IsStaff $false -IsActive $false -DateJoined (Get-Date) -LastLogin (Get-Date) -Groups 0 # PatchedWritableUserRequest |  (optional)

try {
    $Result = Use-rsUsersPartialUpdate -Id $Id -PatchedWritableUserRequest $PatchedWritableUserRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsUsersPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this user. | 
 **PatchedWritableUserRequest** | [**PatchedWritableUserRequest**](PatchedWritableUserRequest.md)|  | [optional] 

### Return type

[**User**](User.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsUsersRetrieve"></a>
# **Use-rsUsersRetrieve**
> User Use-rsUsersRetrieve<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Get a user object.

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

$Id = 56 # Int32 | A unique integer value identifying this user.

try {
    $Result = Use-rsUsersRetrieve -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Use-rsUsersRetrieve: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this user. | 

### Return type

[**User**](User.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Use-rsUsersUpdate"></a>
# **Use-rsUsersUpdate**
> User Use-rsUsersUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableUserRequest] <PSCustomObject><br>



Put a user object.

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

$Id = 56 # Int32 | A unique integer value identifying this user.
$WritableUserRequest = Initialize-WritableUserRequest -Username "MyUsername" -Password "MyPassword" -FirstName "MyFirstName" -LastName "MyLastName" -Email "MyEmail" -IsStaff $false -IsActive $false -DateJoined (Get-Date) -LastLogin (Get-Date) -Groups 0 # WritableUserRequest | 

try {
    $Result = Use-rsUsersUpdate -Id $Id -WritableUserRequest $WritableUserRequest
} catch {
    Write-Host ("Exception occurred when calling Use-rsUsersUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this user. | 
 **WritableUserRequest** | [**WritableUserRequest**](WritableUserRequest.md)|  | 

### Return type

[**User**](User.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

