# InventoryItemTemplateRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceType** | [**NestedDeviceTypeRequest**](NestedDeviceTypeRequest.md) |  | 
**Parent** | **Int32** |  | [optional] 
**Name** | **String** | {module} is accepted as a substitution for the module bay position when attached to a module type. | 
**Label** | **String** | Physical label | [optional] 
**Role** | [**NestedInventoryItemRoleRequest**](NestedInventoryItemRoleRequest.md) |  | [optional] 
**Manufacturer** | [**NestedManufacturerRequest**](NestedManufacturerRequest.md) |  | [optional] 
**PartId** | **String** | Manufacturer-assigned part identifier | [optional] 
**Description** | **String** |  | [optional] 
**ComponentType** | **String** |  | [optional] 
**ComponentId** | **Int64** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$InventoryItemTemplateRequest = Initialize-PSOpenAPIToolsInventoryItemTemplateRequest  -DeviceType null `
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
$InventoryItemTemplateRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

