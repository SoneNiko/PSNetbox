# NestedModuleType
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Manufacturer** | [**NestedManufacturer**](NestedManufacturer.md) |  | [readonly] 
**Model** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$NestedModuleType = Initialize-PSOpenAPIToolsNestedModuleType  -Id null `
 -Url null `
 -Display null `
 -Manufacturer null `
 -Model null
```

- Convert the resource to JSON
```powershell
$NestedModuleType | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

