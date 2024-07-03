# NestedDataFile
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Path** | **String** | File path relative to the data source&#39;s root | [readonly] 

## Examples

- Prepare the resource
```powershell
$NestedDataFile = Initialize-PSOpenAPIToolsNestedDataFile  -Id null `
 -Url null `
 -Display null `
 -Path null
```

- Convert the resource to JSON
```powershell
$NestedDataFile | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

