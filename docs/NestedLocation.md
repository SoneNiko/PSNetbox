# NestedLocation
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Depth** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$NestedLocation = Initialize-PSOpenAPIToolsNestedLocation  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null `
 -Depth null
```

- Convert the resource to JSON
```powershell
$NestedLocation | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

