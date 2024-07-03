# Cluster
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Type** | [**NestedClusterType**](NestedClusterType.md) |  | 
**Group** | [**NestedClusterGroup**](NestedClusterGroup.md) |  | [optional] 
**Status** | [**ClusterStatus**](ClusterStatus.md) |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Site** | [**NestedSite**](NestedSite.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**DeviceCount** | **Int32** |  | [readonly] 
**VirtualmachineCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Cluster = Initialize-PSOpenAPIToolsCluster  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Type null `
 -Group null `
 -Status null `
 -Tenant null `
 -Site null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -DeviceCount null `
 -VirtualmachineCount null
```

- Convert the resource to JSON
```powershell
$Cluster | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

