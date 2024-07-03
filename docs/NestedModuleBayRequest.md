# NestedModuleBayRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InstalledModule** | [**ModuleBayNestedModuleRequest**](ModuleBayNestedModuleRequest.md) |  | [optional] 
**Name** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$NestedModuleBayRequest = Initialize-PSOpenAPIToolsNestedModuleBayRequest  -InstalledModule null `
 -Name null
```

- Convert the resource to JSON
```powershell
$NestedModuleBayRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

