# Location
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Site** | [**NestedSite**](NestedSite.md) |  | 
**Parent** | [**NestedLocation**](NestedLocation.md) |  | [optional] 
**Status** | [**LocationStatus**](LocationStatus.md) |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**RackCount** | **Int32** |  | [readonly] 
**DeviceCount** | **Int32** |  | [readonly] 
**Depth** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Location = Initialize-PSOpenAPIToolsLocation  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null `
 -Site null `
 -Parent null `
 -Status null `
 -Tenant null `
 -Description null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -RackCount null `
 -DeviceCount null `
 -Depth null
```

- Convert the resource to JSON
```powershell
$Location | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

