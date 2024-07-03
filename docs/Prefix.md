# Prefix
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Family** | [**AggregateFamily**](AggregateFamily.md) |  | 
**Prefix** | **String** |  | 
**Site** | [**NestedSite**](NestedSite.md) |  | [optional] 
**Vrf** | [**NestedVRF**](NestedVRF.md) |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Vlan** | [**NestedVLAN**](NestedVLAN.md) |  | [optional] 
**Status** | [**PrefixStatus**](PrefixStatus.md) |  | [optional] 
**Role** | [**NestedRole**](NestedRole.md) |  | [optional] 
**IsPool** | **Boolean** | All IP addresses within this prefix are considered usable | [optional] 
**MarkUtilized** | **Boolean** | Treat as fully utilized | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**Children** | **Int32** |  | [readonly] 
**Depth** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Prefix = Initialize-PSOpenAPIToolsPrefix  -Id null `
 -Url null `
 -Display null `
 -Family null `
 -Prefix null `
 -Site null `
 -Vrf null `
 -Tenant null `
 -Vlan null `
 -Status null `
 -Role null `
 -IsPool null `
 -MarkUtilized null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -Children null `
 -Depth null
```

- Convert the resource to JSON
```powershell
$Prefix | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

