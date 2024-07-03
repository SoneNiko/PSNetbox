# NestedClusterGroup
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Slug** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$NestedClusterGroup = Initialize-PSOpenAPIToolsNestedClusterGroup  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null
```

- Convert the resource to JSON
```powershell
$NestedClusterGroup | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

