# NestedTag
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Color** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$NestedTag = Initialize-PSOpenAPIToolsNestedTag  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null `
 -Color null
```

- Convert the resource to JSON
```powershell
$NestedTag | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

