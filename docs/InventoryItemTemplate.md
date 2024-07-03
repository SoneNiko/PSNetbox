# InventoryItemTemplate
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**DeviceType** | [**NestedDeviceType**](NestedDeviceType.md) |  | 
**Parent** | **Int32** |  | [optional] 
**Name** | **String** | {module} is accepted as a substitution for the module bay position when attached to a module type. | 
**Label** | **String** | Physical label | [optional] 
**Role** | [**NestedInventoryItemRole**](NestedInventoryItemRole.md) |  | [optional] 
**Manufacturer** | [**NestedManufacturer**](NestedManufacturer.md) |  | [optional] 
**PartId** | **String** | Manufacturer-assigned part identifier | [optional] 
**Description** | **String** |  | [optional] 
**ComponentType** | **String** |  | [optional] 
**ComponentId** | **Int64** |  | [optional] 
**Component** | [**AnyType**](.md) |  | [readonly] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**Depth** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$InventoryItemTemplate = Initialize-PSOpenAPIToolsInventoryItemTemplate  -Id null `
 -Url null `
 -Display null `
 -DeviceType null `
 -Parent null `
 -Name null `
 -Label null `
 -Role null `
 -Manufacturer null `
 -PartId null `
 -Description null `
 -ComponentType null `
 -ComponentId null `
 -Component null `
 -Created null `
 -LastUpdated null `
 -Depth null
```

- Convert the resource to JSON
```powershell
$InventoryItemTemplate | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

