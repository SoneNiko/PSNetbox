# PatchedWritableInventoryItemRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Device** | **Int32** |  | [optional] 
**Parent** | **Int32** |  | [optional] 
**Name** | **String** |  | [optional] 
**Label** | **String** | Physical label | [optional] 
**Role** | **Int32** |  | [optional] 
**Manufacturer** | **Int32** |  | [optional] 
**PartId** | **String** | Manufacturer-assigned part identifier | [optional] 
**Serial** | **String** |  | [optional] 
**AssetTag** | **String** | A unique tag used to identify this item | [optional] 
**Discovered** | **Boolean** | This item was automatically discovered | [optional] 
**Description** | **String** |  | [optional] 
**ComponentType** | **String** |  | [optional] 
**ComponentId** | **Int64** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableInventoryItemRequest = Initialize-PSOpenAPIToolsPatchedWritableInventoryItemRequest  -Device null `
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
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableInventoryItemRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

