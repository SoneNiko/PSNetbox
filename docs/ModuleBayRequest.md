# ModuleBayRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Device** | [**NestedDeviceRequest**](NestedDeviceRequest.md) |  | 
**Name** | **String** |  | 
**InstalledModule** | [**ModuleBayNestedModuleRequest**](ModuleBayNestedModuleRequest.md) |  | [optional] 
**Label** | **String** | Physical label | [optional] 
**Position** | **String** | Identifier to reference when renaming installed components | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$ModuleBayRequest = Initialize-PSOpenAPIToolsModuleBayRequest  -Device null `
 -Name null `
 -InstalledModule null `
 -Label null `
 -Position null `
 -Description null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$ModuleBayRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

