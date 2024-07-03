# InventoryItem
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Device** | [**NestedDevice**](NestedDevice.md) |  | 
**Parent** | **Int32** |  | [optional] 
**Name** | **String** |  | 
**Label** | **String** | Physical label | [optional] 
**Role** | [**NestedInventoryItemRole**](NestedInventoryItemRole.md) |  | [optional] 
**Manufacturer** | [**NestedManufacturer**](NestedManufacturer.md) |  | [optional] 
**PartId** | **String** | Manufacturer-assigned part identifier | [optional] 
**Serial** | **String** |  | [optional] 
**AssetTag** | **String** | A unique tag used to identify this item | [optional] 
**Discovered** | **Boolean** | This item was automatically discovered | [optional] 
**Description** | **String** |  | [optional] 
**ComponentType** | **String** |  | [optional] 
**ComponentId** | **Int64** |  | [optional] 
**Component** | [**AnyType**](.md) |  | [readonly] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**Depth** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$InventoryItem = Initialize-PSOpenAPIToolsInventoryItem  -Id null `
 -Url null `
 -Display null `
 -Device null `
 -Parent null `
 -Name null `
 -Label null `
 -Role null `
 -Manufacturer null `
 -PartId null `
 -Serial null `
 -AssetTag null `
 -Discovered null `
 -Description null `
 -ComponentType null `
 -ComponentId null `
 -Component null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -Depth null
```

- Convert the resource to JSON
```powershell
$InventoryItem | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

