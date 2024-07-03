# NestedRegion
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
$NestedRegion = Initialize-PSOpenAPIToolsNestedRegion  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null `
 -Depth null
```

- Convert the resource to JSON
```powershell
$NestedRegion | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

