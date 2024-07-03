# ComponentNestedModule
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Device** | **Int32** |  | 
**ModuleBay** | [**ModuleNestedModuleBay**](ModuleNestedModuleBay.md) |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$ComponentNestedModule = Initialize-PSOpenAPIToolsComponentNestedModule  -Id null `
 -Url null `
 -Display null `
 -Device null `
 -ModuleBay null
```

- Convert the resource to JSON
```powershell
$ComponentNestedModule | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

