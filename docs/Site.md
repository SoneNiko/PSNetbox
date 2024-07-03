# Site
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** | Full name of the site | 
**Slug** | **String** |  | 
**Status** | [**LocationStatus**](LocationStatus.md) |  | [optional] 
**Region** | [**NestedRegion**](NestedRegion.md) |  | [optional] 
**Group** | [**NestedSiteGroup**](NestedSiteGroup.md) |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Facility** | **String** | Local facility ID or description | [optional] 
**TimeZone** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**PhysicalAddress** | **String** | Physical location of the building | [optional] 
**ShippingAddress** | **String** | If different from the physical address | [optional] 
**Latitude** | **Double** | GPS coordinate in decimal format (xx.yyyyyy) | [optional] 
**Longitude** | **Double** | GPS coordinate in decimal format (xx.yyyyyy) | [optional] 
**Comments** | **String** |  | [optional] 
**Asns** | **Int32[]** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**CircuitCount** | **Int32** |  | [readonly] 
**DeviceCount** | **Int32** |  | [readonly] 
**PrefixCount** | **Int32** |  | [readonly] 
**RackCount** | **Int32** |  | [readonly] 
**VirtualmachineCount** | **Int32** |  | [readonly] 
**VlanCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Site = Initialize-PSOpenAPIToolsSite  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null `
 -Status null `
 -Region null `
 -Group null `
 -Tenant null `
 -Facility null `
 -TimeZone null `
 -Description null `
 -PhysicalAddress null `
 -ShippingAddress null `
 -Latitude null `
 -Longitude null `
 -Comments null `
 -Asns null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -CircuitCount null `
 -DeviceCount null `
 -PrefixCount null `
 -RackCount null `
 -VirtualmachineCount null `
 -VlanCount null
```

- Convert the resource to JSON
```powershell
$Site | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

