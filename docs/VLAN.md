# VLAN
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Site** | [**NestedSite**](NestedSite.md) |  | [optional] 
**Group** | [**NestedVLANGroup**](NestedVLANGroup.md) |  | [optional] 
**Vid** | **Int32** | Numeric VLAN ID (1-4094) | 
**Name** | **String** |  | 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Status** | [**IPRangeStatus**](IPRangeStatus.md) |  | [optional] 
**Role** | [**NestedRole**](NestedRole.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**L2vpnTermination** | [**NestedL2VPNTermination**](NestedL2VPNTermination.md) |  | [readonly] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**PrefixCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$VLAN = Initialize-PSOpenAPIToolsVLAN  -Id null `
 -Url null `
 -Display null `
 -Site null `
 -Group null `
 -Vid null `
 -Name null `
 -Tenant null `
 -Status null `
 -Role null `
 -Description null `
 -Comments null `
 -L2vpnTermination null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -PrefixCount null
```

- Convert the resource to JSON
```powershell
$VLAN | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

