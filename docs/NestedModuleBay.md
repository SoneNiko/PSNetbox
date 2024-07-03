# NestedModuleBay
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**InstalledModule** | [**ModuleBayNestedModule**](ModuleBayNestedModule.md) |  | [optional] 
**Name** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$NestedModuleBay = Initialize-PSOpenAPIToolsNestedModuleBay  -Id null `
 -Url null `
 -Display null `
 -InstalledModule null `
 -Name null
```

- Convert the resource to JSON
```powershell
$NestedModuleBay | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

