# NestedRole
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
$NestedRole = Initialize-PSOpenAPIToolsNestedRole  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null
```

- Convert the resource to JSON
```powershell
$NestedRole | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

