# Manufacturer
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**DevicetypeCount** | **Int32** |  | [readonly] 
**InventoryitemCount** | **Int32** |  | [readonly] 
**PlatformCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Manufacturer = Initialize-PSOpenAPIToolsManufacturer  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null `
 -Description null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -DevicetypeCount null `
 -InventoryitemCount null `
 -PlatformCount null
```

- Convert the resource to JSON
```powershell
$Manufacturer | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

