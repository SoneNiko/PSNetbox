# DataFile
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Source** | [**NestedDataSource**](NestedDataSource.md) |  | [readonly] 
**Path** | **String** | File path relative to the data source&#39;s root | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**Size** | **Int32** |  | [readonly] 
**Hash** | **String** | SHA256 hash of the file data | [readonly] 

## Examples

- Prepare the resource
```powershell
$DataFile = Initialize-PSOpenAPIToolsDataFile  -Id null `
 -Url null `
 -Display null `
 -Source null `
 -Path null `
 -LastUpdated null `
 -Size null `
 -Hash null
```

- Convert the resource to JSON
```powershell
$DataFile | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

