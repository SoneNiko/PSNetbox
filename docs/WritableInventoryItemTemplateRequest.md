# WritableInventoryItemTemplateRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceType** | **Int32** |  | 
**Parent** | **Int32** |  | [optional] 
**Name** | **String** | {module} is accepted as a substitution for the module bay position when attached to a module type. | 
**Label** | **String** | Physical label | [optional] 
**Role** | **Int32** |  | [optional] 
**Manufacturer** | **Int32** |  | [optional] 
**PartId** | **String** | Manufacturer-assigned part identifier | [optional] 
**Description** | **String** |  | [optional] 
**ComponentType** | **String** |  | [optional] 
**ComponentId** | **Int64** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableInventoryItemTemplateRequest = Initialize-PSOpenAPIToolsWritableInventoryItemTemplateRequest  -DeviceType null `
 -Parent null `
 -Name null `
 -Label null `
 -Role null `
 -Manufacturer null `
 -PartId null `
 -Description null `
 -ComponentType null `
 -ComponentId null
```

- Convert the resource to JSON
```powershell
$WritableInventoryItemTemplateRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

