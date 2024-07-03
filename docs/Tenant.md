# Tenant
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Group** | [**NestedTenantGroup**](NestedTenantGroup.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**CircuitCount** | **Int32** |  | [readonly] 
**DeviceCount** | **Int32** |  | [readonly] 
**IpaddressCount** | **Int32** |  | [readonly] 
**PrefixCount** | **Int32** |  | [readonly] 
**RackCount** | **Int32** |  | [readonly] 
**SiteCount** | **Int32** |  | [readonly] 
**VirtualmachineCount** | **Int32** |  | [readonly] 
**VlanCount** | **Int32** |  | [readonly] 
**VrfCount** | **Int32** |  | [readonly] 
**ClusterCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Tenant = Initialize-PSOpenAPIToolsTenant  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null `
 -Group null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -CircuitCount null `
 -DeviceCount null `
 -IpaddressCount null `
 -PrefixCount null `
 -RackCount null `
 -SiteCount null `
 -VirtualmachineCount null `
 -VlanCount null `
 -VrfCount null `
 -ClusterCount null
```

- Convert the resource to JSON
```powershell
$Tenant | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

