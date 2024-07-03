# PSOpenAPITools.PSOpenAPITools\Api.CoreApi

All URIs are relative to *https://netbox.grid.uchicago.edu/api/schema*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Invoke-CoreDataFilesList**](CoreApi.md#Invoke-CoreDataFilesList) | **GET** /api/core/data-files/ | 
[**Invoke-CoreDataFilesRetrieve**](CoreApi.md#Invoke-CoreDataFilesRetrieve) | **GET** /api/core/data-files/{id}/ | 
[**Invoke-CoreDataSourcesBulkDestroy**](CoreApi.md#Invoke-CoreDataSourcesBulkDestroy) | **DELETE** /api/core/data-sources/ | 
[**Invoke-CoreDataSourcesBulkPartialUpdate**](CoreApi.md#Invoke-CoreDataSourcesBulkPartialUpdate) | **PATCH** /api/core/data-sources/ | 
[**Invoke-CoreDataSourcesBulkUpdate**](CoreApi.md#Invoke-CoreDataSourcesBulkUpdate) | **PUT** /api/core/data-sources/ | 
[**Invoke-CoreDataSourcesCreate**](CoreApi.md#Invoke-CoreDataSourcesCreate) | **POST** /api/core/data-sources/ | 
[**Invoke-CoreDataSourcesDestroy**](CoreApi.md#Invoke-CoreDataSourcesDestroy) | **DELETE** /api/core/data-sources/{id}/ | 
[**Invoke-CoreDataSourcesList**](CoreApi.md#Invoke-CoreDataSourcesList) | **GET** /api/core/data-sources/ | 
[**Invoke-CoreDataSourcesPartialUpdate**](CoreApi.md#Invoke-CoreDataSourcesPartialUpdate) | **PATCH** /api/core/data-sources/{id}/ | 
[**Invoke-CoreDataSourcesRetrieve**](CoreApi.md#Invoke-CoreDataSourcesRetrieve) | **GET** /api/core/data-sources/{id}/ | 
[**Invoke-CoreDataSourcesSyncCreate**](CoreApi.md#Invoke-CoreDataSourcesSyncCreate) | **POST** /api/core/data-sources/{id}/sync/ | 
[**Invoke-CoreDataSourcesUpdate**](CoreApi.md#Invoke-CoreDataSourcesUpdate) | **PUT** /api/core/data-sources/{id}/ | 
[**Invoke-CoreJobsList**](CoreApi.md#Invoke-CoreJobsList) | **GET** /api/core/jobs/ | 
[**Invoke-CoreJobsRetrieve**](CoreApi.md#Invoke-CoreJobsRetrieve) | **GET** /api/core/jobs/{id}/ | 


<a id="Invoke-CoreDataFilesList"></a>
# **Invoke-CoreDataFilesList**
> PaginatedDataFileList Invoke-CoreDataFilesList<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Created] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedEmpty] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedGt] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedGte] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedLt] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedLte] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedN] <System.Nullable[System.DateTime][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedByRequest] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Hash] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-HashEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-HashIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-HashIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-HashIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-HashIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-HashN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-HashNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-HashNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-HashNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-HashNisw] <String[]><br>
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
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Path] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PathEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PathIc] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PathIe] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PathIew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PathIsw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PathN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PathNic] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PathNie] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PathNiew] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PathNisw] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Q] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Size] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SizeEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SizeGt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SizeGte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SizeLt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SizeLte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SizeN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Source] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SourceN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SourceId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-SourceIdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UpdatedByRequest] <String><br>



Get a list of data file objects.

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
$Hash = "MyHash" # String[] |  (optional)
$HashEmpty = $true # Boolean |  (optional)
$HashIc = "MyHashIc" # String[] |  (optional)
$HashIe = "MyHashIe" # String[] |  (optional)
$HashIew = "MyHashIew" # String[] |  (optional)
$HashIsw = "MyHashIsw" # String[] |  (optional)
$HashN = "MyHashN" # String[] |  (optional)
$HashNic = "MyHashNic" # String[] |  (optional)
$HashNie = "MyHashNie" # String[] |  (optional)
$HashNiew = "MyHashNiew" # String[] |  (optional)
$HashNisw = "MyHashNisw" # String[] |  (optional)
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
$Path = "MyPath" # String[] |  (optional)
$PathEmpty = $true # Boolean |  (optional)
$PathIc = "MyPathIc" # String[] |  (optional)
$PathIe = "MyPathIe" # String[] |  (optional)
$PathIew = "MyPathIew" # String[] |  (optional)
$PathIsw = "MyPathIsw" # String[] |  (optional)
$PathN = "MyPathN" # String[] |  (optional)
$PathNic = "MyPathNic" # String[] |  (optional)
$PathNie = "MyPathNie" # String[] |  (optional)
$PathNiew = "MyPathNiew" # String[] |  (optional)
$PathNisw = "MyPathNisw" # String[] |  (optional)
$Q = "MyQ" # String |  (optional)
$Size = 0 # Int32[] |  (optional)
$SizeEmpty = $true # Boolean |  (optional)
$SizeGt = 0 # Int32[] |  (optional)
$SizeGte = 0 # Int32[] |  (optional)
$SizeLt = 0 # Int32[] |  (optional)
$SizeLte = 0 # Int32[] |  (optional)
$SizeN = 0 # Int32[] |  (optional)
$Source = "MySource" # String[] | Data source (name) (optional)
$SourceN = "MySourceN" # String[] | Data source (name) (optional)
$SourceId = 0 # Int32[] | Data source (ID) (optional)
$SourceIdN = 0 # Int32[] | Data source (ID) (optional)
$UpdatedByRequest = "38400000-8cf0-11bd-b23e-10b96e4ef00d" # String |  (optional)

try {
    $Result = Invoke-CoreDataFilesList -Created $Created -CreatedEmpty $CreatedEmpty -CreatedGt $CreatedGt -CreatedGte $CreatedGte -CreatedLt $CreatedLt -CreatedLte $CreatedLte -CreatedN $CreatedN -CreatedByRequest $CreatedByRequest -Hash $Hash -HashEmpty $HashEmpty -HashIc $HashIc -HashIe $HashIe -HashIew $HashIew -HashIsw $HashIsw -HashN $HashN -HashNic $HashNic -HashNie $HashNie -HashNiew $HashNiew -HashNisw $HashNisw -Id $Id -IdEmpty $IdEmpty -IdGt $IdGt -IdGte $IdGte -IdLt $IdLt -IdLte $IdLte -IdN $IdN -LastUpdated $LastUpdated -LastUpdatedEmpty $LastUpdatedEmpty -LastUpdatedGt $LastUpdatedGt -LastUpdatedGte $LastUpdatedGte -LastUpdatedLt $LastUpdatedLt -LastUpdatedLte $LastUpdatedLte -LastUpdatedN $LastUpdatedN -Limit $Limit -ModifiedByRequest $ModifiedByRequest -Offset $Offset -Ordering $Ordering -Path $Path -PathEmpty $PathEmpty -PathIc $PathIc -PathIe $PathIe -PathIew $PathIew -PathIsw $PathIsw -PathN $PathN -PathNic $PathNic -PathNie $PathNie -PathNiew $PathNiew -PathNisw $PathNisw -Q $Q -Size $Size -SizeEmpty $SizeEmpty -SizeGt $SizeGt -SizeGte $SizeGte -SizeLt $SizeLt -SizeLte $SizeLte -SizeN $SizeN -Source $Source -SourceN $SourceN -SourceId $SourceId -SourceIdN $SourceIdN -UpdatedByRequest $UpdatedByRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-CoreDataFilesList: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
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
 **Hash** | [**String[]**](String.md)|  | [optional] 
 **HashEmpty** | **Boolean**|  | [optional] 
 **HashIc** | [**String[]**](String.md)|  | [optional] 
 **HashIe** | [**String[]**](String.md)|  | [optional] 
 **HashIew** | [**String[]**](String.md)|  | [optional] 
 **HashIsw** | [**String[]**](String.md)|  | [optional] 
 **HashN** | [**String[]**](String.md)|  | [optional] 
 **HashNic** | [**String[]**](String.md)|  | [optional] 
 **HashNie** | [**String[]**](String.md)|  | [optional] 
 **HashNiew** | [**String[]**](String.md)|  | [optional] 
 **HashNisw** | [**String[]**](String.md)|  | [optional] 
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
 **Path** | [**String[]**](String.md)|  | [optional] 
 **PathEmpty** | **Boolean**|  | [optional] 
 **PathIc** | [**String[]**](String.md)|  | [optional] 
 **PathIe** | [**String[]**](String.md)|  | [optional] 
 **PathIew** | [**String[]**](String.md)|  | [optional] 
 **PathIsw** | [**String[]**](String.md)|  | [optional] 
 **PathN** | [**String[]**](String.md)|  | [optional] 
 **PathNic** | [**String[]**](String.md)|  | [optional] 
 **PathNie** | [**String[]**](String.md)|  | [optional] 
 **PathNiew** | [**String[]**](String.md)|  | [optional] 
 **PathNisw** | [**String[]**](String.md)|  | [optional] 
 **Q** | **String**|  | [optional] 
 **Size** | [**Int32[]**](Int32.md)|  | [optional] 
 **SizeEmpty** | **Boolean**|  | [optional] 
 **SizeGt** | [**Int32[]**](Int32.md)|  | [optional] 
 **SizeGte** | [**Int32[]**](Int32.md)|  | [optional] 
 **SizeLt** | [**Int32[]**](Int32.md)|  | [optional] 
 **SizeLte** | [**Int32[]**](Int32.md)|  | [optional] 
 **SizeN** | [**Int32[]**](Int32.md)|  | [optional] 
 **Source** | [**String[]**](String.md)| Data source (name) | [optional] 
 **SourceN** | [**String[]**](String.md)| Data source (name) | [optional] 
 **SourceId** | [**Int32[]**](Int32.md)| Data source (ID) | [optional] 
 **SourceIdN** | [**Int32[]**](Int32.md)| Data source (ID) | [optional] 
 **UpdatedByRequest** | **String**|  | [optional] 

### Return type

[**PaginatedDataFileList**](PaginatedDataFileList.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-CoreDataFilesRetrieve"></a>
# **Invoke-CoreDataFilesRetrieve**
> DataFile Invoke-CoreDataFilesRetrieve<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Get a data file object.

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

$Id = 56 # Int32 | A unique integer value identifying this data file.

try {
    $Result = Invoke-CoreDataFilesRetrieve -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Invoke-CoreDataFilesRetrieve: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this data file. | 

### Return type

[**DataFile**](DataFile.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-CoreDataSourcesBulkDestroy"></a>
# **Invoke-CoreDataSourcesBulkDestroy**
> void Invoke-CoreDataSourcesBulkDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DataSourceRequest] <PSCustomObject[]><br>



Delete a list of data source objects.

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

$DataSourceRequest = Initialize-DataSourceRequest -Name "MyName" -Type "null" -SourceUrl "MySourceUrl" -Enabled $false -Description "MyDescription" -Comments "MyComments" -Parameters  -IgnoreRules "MyIgnoreRules" -CustomFields @{ key_example =  } # DataSourceRequest[] | 

try {
    $Result = Invoke-CoreDataSourcesBulkDestroy -DataSourceRequest $DataSourceRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-CoreDataSourcesBulkDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **DataSourceRequest** | [**DataSourceRequest[]**](DataSourceRequest.md)|  | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-CoreDataSourcesBulkPartialUpdate"></a>
# **Invoke-CoreDataSourcesBulkPartialUpdate**
> DataSource[] Invoke-CoreDataSourcesBulkPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DataSourceRequest] <PSCustomObject[]><br>



Patch a list of data source objects.

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

$DataSourceRequest = Initialize-DataSourceRequest -Name "MyName" -Type "null" -SourceUrl "MySourceUrl" -Enabled $false -Description "MyDescription" -Comments "MyComments" -Parameters  -IgnoreRules "MyIgnoreRules" -CustomFields @{ key_example =  } # DataSourceRequest[] | 

try {
    $Result = Invoke-CoreDataSourcesBulkPartialUpdate -DataSourceRequest $DataSourceRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-CoreDataSourcesBulkPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **DataSourceRequest** | [**DataSourceRequest[]**](DataSourceRequest.md)|  | 

### Return type

[**DataSource[]**](DataSource.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-CoreDataSourcesBulkUpdate"></a>
# **Invoke-CoreDataSourcesBulkUpdate**
> DataSource[] Invoke-CoreDataSourcesBulkUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-DataSourceRequest] <PSCustomObject[]><br>



Put a list of data source objects.

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

$DataSourceRequest = Initialize-DataSourceRequest -Name "MyName" -Type "null" -SourceUrl "MySourceUrl" -Enabled $false -Description "MyDescription" -Comments "MyComments" -Parameters  -IgnoreRules "MyIgnoreRules" -CustomFields @{ key_example =  } # DataSourceRequest[] | 

try {
    $Result = Invoke-CoreDataSourcesBulkUpdate -DataSourceRequest $DataSourceRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-CoreDataSourcesBulkUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **DataSourceRequest** | [**DataSourceRequest[]**](DataSourceRequest.md)|  | 

### Return type

[**DataSource[]**](DataSource.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-CoreDataSourcesCreate"></a>
# **Invoke-CoreDataSourcesCreate**
> DataSource Invoke-CoreDataSourcesCreate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableDataSourceRequest] <PSCustomObject><br>



Post a list of data source objects.

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

$WritableDataSourceRequest = Initialize-WritableDataSourceRequest -Name "MyName" -Type "MyType" -SourceUrl "MySourceUrl" -Enabled $false -Description "MyDescription" -Comments "MyComments" -Parameters  -IgnoreRules "MyIgnoreRules" -CustomFields @{ key_example =  } # WritableDataSourceRequest | 

try {
    $Result = Invoke-CoreDataSourcesCreate -WritableDataSourceRequest $WritableDataSourceRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-CoreDataSourcesCreate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **WritableDataSourceRequest** | [**WritableDataSourceRequest**](WritableDataSourceRequest.md)|  | 

### Return type

[**DataSource**](DataSource.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-CoreDataSourcesDestroy"></a>
# **Invoke-CoreDataSourcesDestroy**
> void Invoke-CoreDataSourcesDestroy<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Delete a data source object.

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

$Id = 56 # Int32 | A unique integer value identifying this data source.

try {
    $Result = Invoke-CoreDataSourcesDestroy -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Invoke-CoreDataSourcesDestroy: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this data source. | 

### Return type

void (empty response body)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-CoreDataSourcesList"></a>
# **Invoke-CoreDataSourcesList**
> PaginatedDataSourceList Invoke-CoreDataSourcesList<br>
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
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Enabled] <System.Nullable[Boolean]><br>
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
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Q] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Status] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-StatusN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Tag] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TagN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Type] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-TypeN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UpdatedByRequest] <String><br>



Get a list of data source objects.

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
$Enabled = $true # Boolean |  (optional)
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
$Q = "MyQ" # String | Search (optional)
$Status = "MyStatus" # String[] |  (optional)
$StatusN = "MyStatusN" # String[] |  (optional)
$Tag = "MyTag" # String[] |  (optional)
$TagN = "MyTagN" # String[] |  (optional)
$Type = "MyType" # String[] |  (optional)
$TypeN = "MyTypeN" # String[] |  (optional)
$UpdatedByRequest = "38400000-8cf0-11bd-b23e-10b96e4ef00d" # String |  (optional)

try {
    $Result = Invoke-CoreDataSourcesList -Created $Created -CreatedEmpty $CreatedEmpty -CreatedGt $CreatedGt -CreatedGte $CreatedGte -CreatedLt $CreatedLt -CreatedLte $CreatedLte -CreatedN $CreatedN -CreatedByRequest $CreatedByRequest -Description $Description -DescriptionEmpty $DescriptionEmpty -DescriptionIc $DescriptionIc -DescriptionIe $DescriptionIe -DescriptionIew $DescriptionIew -DescriptionIsw $DescriptionIsw -DescriptionN $DescriptionN -DescriptionNic $DescriptionNic -DescriptionNie $DescriptionNie -DescriptionNiew $DescriptionNiew -DescriptionNisw $DescriptionNisw -Enabled $Enabled -Id $Id -IdEmpty $IdEmpty -IdGt $IdGt -IdGte $IdGte -IdLt $IdLt -IdLte $IdLte -IdN $IdN -LastUpdated $LastUpdated -LastUpdatedEmpty $LastUpdatedEmpty -LastUpdatedGt $LastUpdatedGt -LastUpdatedGte $LastUpdatedGte -LastUpdatedLt $LastUpdatedLt -LastUpdatedLte $LastUpdatedLte -LastUpdatedN $LastUpdatedN -Limit $Limit -ModifiedByRequest $ModifiedByRequest -Name $Name -NameEmpty $NameEmpty -NameIc $NameIc -NameIe $NameIe -NameIew $NameIew -NameIsw $NameIsw -NameN $NameN -NameNic $NameNic -NameNie $NameNie -NameNiew $NameNiew -NameNisw $NameNisw -Offset $Offset -Ordering $Ordering -Q $Q -Status $Status -StatusN $StatusN -Tag $Tag -TagN $TagN -Type $Type -TypeN $TypeN -UpdatedByRequest $UpdatedByRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-CoreDataSourcesList: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
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
 **Enabled** | **Boolean**|  | [optional] 
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
 **Q** | **String**| Search | [optional] 
 **Status** | [**String[]**](String.md)|  | [optional] 
 **StatusN** | [**String[]**](String.md)|  | [optional] 
 **Tag** | [**String[]**](String.md)|  | [optional] 
 **TagN** | [**String[]**](String.md)|  | [optional] 
 **Type** | [**String[]**](String.md)|  | [optional] 
 **TypeN** | [**String[]**](String.md)|  | [optional] 
 **UpdatedByRequest** | **String**|  | [optional] 

### Return type

[**PaginatedDataSourceList**](PaginatedDataSourceList.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-CoreDataSourcesPartialUpdate"></a>
# **Invoke-CoreDataSourcesPartialUpdate**
> DataSource Invoke-CoreDataSourcesPartialUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-PatchedWritableDataSourceRequest] <PSCustomObject><br>



Patch a data source object.

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

$Id = 56 # Int32 | A unique integer value identifying this data source.
$PatchedWritableDataSourceRequest = Initialize-PatchedWritableDataSourceRequest -Name "MyName" -Type "MyType" -SourceUrl "MySourceUrl" -Enabled $false -Description "MyDescription" -Comments "MyComments" -Parameters  -IgnoreRules "MyIgnoreRules" -CustomFields @{ key_example =  } # PatchedWritableDataSourceRequest |  (optional)

try {
    $Result = Invoke-CoreDataSourcesPartialUpdate -Id $Id -PatchedWritableDataSourceRequest $PatchedWritableDataSourceRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-CoreDataSourcesPartialUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this data source. | 
 **PatchedWritableDataSourceRequest** | [**PatchedWritableDataSourceRequest**](PatchedWritableDataSourceRequest.md)|  | [optional] 

### Return type

[**DataSource**](DataSource.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-CoreDataSourcesRetrieve"></a>
# **Invoke-CoreDataSourcesRetrieve**
> DataSource Invoke-CoreDataSourcesRetrieve<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Get a data source object.

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

$Id = 56 # Int32 | A unique integer value identifying this data source.

try {
    $Result = Invoke-CoreDataSourcesRetrieve -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Invoke-CoreDataSourcesRetrieve: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this data source. | 

### Return type

[**DataSource**](DataSource.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-CoreDataSourcesSyncCreate"></a>
# **Invoke-CoreDataSourcesSyncCreate**
> DataSource Invoke-CoreDataSourcesSyncCreate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableDataSourceRequest] <PSCustomObject><br>



Enqueue a job to synchronize the DataSource.

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

$Id = 56 # Int32 | A unique integer value identifying this data source.
$WritableDataSourceRequest = Initialize-WritableDataSourceRequest -Name "MyName" -Type "MyType" -SourceUrl "MySourceUrl" -Enabled $false -Description "MyDescription" -Comments "MyComments" -Parameters  -IgnoreRules "MyIgnoreRules" -CustomFields @{ key_example =  } # WritableDataSourceRequest | 

try {
    $Result = Invoke-CoreDataSourcesSyncCreate -Id $Id -WritableDataSourceRequest $WritableDataSourceRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-CoreDataSourcesSyncCreate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this data source. | 
 **WritableDataSourceRequest** | [**WritableDataSourceRequest**](WritableDataSourceRequest.md)|  | 

### Return type

[**DataSource**](DataSource.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-CoreDataSourcesUpdate"></a>
# **Invoke-CoreDataSourcesUpdate**
> DataSource Invoke-CoreDataSourcesUpdate<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-WritableDataSourceRequest] <PSCustomObject><br>



Put a data source object.

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

$Id = 56 # Int32 | A unique integer value identifying this data source.
$WritableDataSourceRequest = Initialize-WritableDataSourceRequest -Name "MyName" -Type "MyType" -SourceUrl "MySourceUrl" -Enabled $false -Description "MyDescription" -Comments "MyComments" -Parameters  -IgnoreRules "MyIgnoreRules" -CustomFields @{ key_example =  } # WritableDataSourceRequest | 

try {
    $Result = Invoke-CoreDataSourcesUpdate -Id $Id -WritableDataSourceRequest $WritableDataSourceRequest
} catch {
    Write-Host ("Exception occurred when calling Invoke-CoreDataSourcesUpdate: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this data source. | 
 **WritableDataSourceRequest** | [**WritableDataSourceRequest**](WritableDataSourceRequest.md)|  | 

### Return type

[**DataSource**](DataSource.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: application/json, multipart/form-data
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-CoreJobsList"></a>
# **Invoke-CoreJobsList**
> PaginatedJobList Invoke-CoreJobsList<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Completed] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CompletedAfter] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CompletedBefore] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Created] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedAfter] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-CreatedBefore] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdGte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdLte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Interval] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IntervalEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IntervalGt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IntervalGte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IntervalLt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IntervalLte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-IntervalN] <System.Nullable[Int32][]><br>
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
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ObjectId] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ObjectIdEmpty] <System.Nullable[Boolean]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ObjectIdGt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ObjectIdGte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ObjectIdLt] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ObjectIdLte] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ObjectIdN] <System.Nullable[Int32][]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ObjectType] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ObjectTypeN] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Offset] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Ordering] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Q] <String><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Scheduled] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ScheduledAfter] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-ScheduledBefore] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Started] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-StartedAfter] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-StartedBefore] <System.Nullable[System.DateTime]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Status] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-StatusN] <String[]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-User] <System.Nullable[Int32]><br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-UserN] <System.Nullable[Int32]><br>



Retrieve a list of job results

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

$Completed = (Get-Date) # System.DateTime |  (optional)
$CompletedAfter = (Get-Date) # System.DateTime |  (optional)
$CompletedBefore = (Get-Date) # System.DateTime |  (optional)
$Created = (Get-Date) # System.DateTime |  (optional)
$CreatedAfter = (Get-Date) # System.DateTime |  (optional)
$CreatedBefore = (Get-Date) # System.DateTime |  (optional)
$Id = 0 # Int32[] |  (optional)
$IdEmpty = $true # Boolean |  (optional)
$IdGt = 0 # Int32[] |  (optional)
$IdGte = 0 # Int32[] |  (optional)
$IdLt = 0 # Int32[] |  (optional)
$IdLte = 0 # Int32[] |  (optional)
$IdN = 0 # Int32[] |  (optional)
$Interval = 0 # Int32[] |  (optional)
$IntervalEmpty = $true # Boolean |  (optional)
$IntervalGt = 0 # Int32[] |  (optional)
$IntervalGte = 0 # Int32[] |  (optional)
$IntervalLt = 0 # Int32[] |  (optional)
$IntervalLte = 0 # Int32[] |  (optional)
$IntervalN = 0 # Int32[] |  (optional)
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
$ObjectId = 0 # Int32[] |  (optional)
$ObjectIdEmpty = $true # Boolean |  (optional)
$ObjectIdGt = 0 # Int32[] |  (optional)
$ObjectIdGte = 0 # Int32[] |  (optional)
$ObjectIdLt = 0 # Int32[] |  (optional)
$ObjectIdLte = 0 # Int32[] |  (optional)
$ObjectIdN = 0 # Int32[] |  (optional)
$ObjectType = 56 # Int32 |  (optional)
$ObjectTypeN = 56 # Int32 |  (optional)
$Offset = 56 # Int32 | The initial index from which to return the results. (optional)
$Ordering = "MyOrdering" # String | Which field to use when ordering the results. (optional)
$Q = "MyQ" # String | Search (optional)
$Scheduled = (Get-Date) # System.DateTime |  (optional)
$ScheduledAfter = (Get-Date) # System.DateTime |  (optional)
$ScheduledBefore = (Get-Date) # System.DateTime |  (optional)
$Started = (Get-Date) # System.DateTime |  (optional)
$StartedAfter = (Get-Date) # System.DateTime |  (optional)
$StartedBefore = (Get-Date) # System.DateTime |  (optional)
$Status = "MyStatus" # String[] |  (optional)
$StatusN = "MyStatusN" # String[] |  (optional)
$User = 56 # Int32 |  (optional)
$UserN = 56 # Int32 |  (optional)

try {
    $Result = Invoke-CoreJobsList -Completed $Completed -CompletedAfter $CompletedAfter -CompletedBefore $CompletedBefore -Created $Created -CreatedAfter $CreatedAfter -CreatedBefore $CreatedBefore -Id $Id -IdEmpty $IdEmpty -IdGt $IdGt -IdGte $IdGte -IdLt $IdLt -IdLte $IdLte -IdN $IdN -Interval $Interval -IntervalEmpty $IntervalEmpty -IntervalGt $IntervalGt -IntervalGte $IntervalGte -IntervalLt $IntervalLt -IntervalLte $IntervalLte -IntervalN $IntervalN -Limit $Limit -Name $Name -NameEmpty $NameEmpty -NameIc $NameIc -NameIe $NameIe -NameIew $NameIew -NameIsw $NameIsw -NameN $NameN -NameNic $NameNic -NameNie $NameNie -NameNiew $NameNiew -NameNisw $NameNisw -ObjectId $ObjectId -ObjectIdEmpty $ObjectIdEmpty -ObjectIdGt $ObjectIdGt -ObjectIdGte $ObjectIdGte -ObjectIdLt $ObjectIdLt -ObjectIdLte $ObjectIdLte -ObjectIdN $ObjectIdN -ObjectType $ObjectType -ObjectTypeN $ObjectTypeN -Offset $Offset -Ordering $Ordering -Q $Q -Scheduled $Scheduled -ScheduledAfter $ScheduledAfter -ScheduledBefore $ScheduledBefore -Started $Started -StartedAfter $StartedAfter -StartedBefore $StartedBefore -Status $Status -StatusN $StatusN -User $User -UserN $UserN
} catch {
    Write-Host ("Exception occurred when calling Invoke-CoreJobsList: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Completed** | **System.DateTime**|  | [optional] 
 **CompletedAfter** | **System.DateTime**|  | [optional] 
 **CompletedBefore** | **System.DateTime**|  | [optional] 
 **Created** | **System.DateTime**|  | [optional] 
 **CreatedAfter** | **System.DateTime**|  | [optional] 
 **CreatedBefore** | **System.DateTime**|  | [optional] 
 **Id** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdEmpty** | **Boolean**|  | [optional] 
 **IdGt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdGte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdLte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IdN** | [**Int32[]**](Int32.md)|  | [optional] 
 **Interval** | [**Int32[]**](Int32.md)|  | [optional] 
 **IntervalEmpty** | **Boolean**|  | [optional] 
 **IntervalGt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IntervalGte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IntervalLt** | [**Int32[]**](Int32.md)|  | [optional] 
 **IntervalLte** | [**Int32[]**](Int32.md)|  | [optional] 
 **IntervalN** | [**Int32[]**](Int32.md)|  | [optional] 
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
 **ObjectId** | [**Int32[]**](Int32.md)|  | [optional] 
 **ObjectIdEmpty** | **Boolean**|  | [optional] 
 **ObjectIdGt** | [**Int32[]**](Int32.md)|  | [optional] 
 **ObjectIdGte** | [**Int32[]**](Int32.md)|  | [optional] 
 **ObjectIdLt** | [**Int32[]**](Int32.md)|  | [optional] 
 **ObjectIdLte** | [**Int32[]**](Int32.md)|  | [optional] 
 **ObjectIdN** | [**Int32[]**](Int32.md)|  | [optional] 
 **ObjectType** | **Int32**|  | [optional] 
 **ObjectTypeN** | **Int32**|  | [optional] 
 **Offset** | **Int32**| The initial index from which to return the results. | [optional] 
 **Ordering** | **String**| Which field to use when ordering the results. | [optional] 
 **Q** | **String**| Search | [optional] 
 **Scheduled** | **System.DateTime**|  | [optional] 
 **ScheduledAfter** | **System.DateTime**|  | [optional] 
 **ScheduledBefore** | **System.DateTime**|  | [optional] 
 **Started** | **System.DateTime**|  | [optional] 
 **StartedAfter** | **System.DateTime**|  | [optional] 
 **StartedBefore** | **System.DateTime**|  | [optional] 
 **Status** | [**String[]**](String.md)|  | [optional] 
 **StatusN** | [**String[]**](String.md)|  | [optional] 
 **User** | **Int32**|  | [optional] 
 **UserN** | **Int32**|  | [optional] 

### Return type

[**PaginatedJobList**](PaginatedJobList.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

<a id="Invoke-CoreJobsRetrieve"></a>
# **Invoke-CoreJobsRetrieve**
> Job Invoke-CoreJobsRetrieve<br>
> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[-Id] <Int32><br>



Retrieve a list of job results

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

$Id = 56 # Int32 | A unique integer value identifying this job.

try {
    $Result = Invoke-CoreJobsRetrieve -Id $Id
} catch {
    Write-Host ("Exception occurred when calling Invoke-CoreJobsRetrieve: {0}" -f ($_.ErrorDetails | ConvertFrom-Json))
    Write-Host ("Response headers: {0}" -f ($_.Exception.Response.Headers | ConvertTo-Json))
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **Id** | **Int32**| A unique integer value identifying this job. | 

### Return type

[**Job**](Job.md) (PSCustomObject)

### Authorization

[cookieAuth](../README.md#cookieAuth), [tokenAuth](../README.md#tokenAuth)

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

