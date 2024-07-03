# VirtualMachineWithConfigContext
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Status** | [**ModuleStatus**](ModuleStatus.md) |  | [optional] 
**Site** | [**NestedSite**](NestedSite.md) |  | [optional] 
**Cluster** | [**NestedCluster**](NestedCluster.md) |  | [optional] 
**Device** | [**NestedDevice**](NestedDevice.md) |  | [optional] 
**Role** | [**NestedDeviceRole**](NestedDeviceRole.md) |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Platform** | [**NestedPlatform**](NestedPlatform.md) |  | [optional] 
**PrimaryIp** | [**NestedIPAddress**](NestedIPAddress.md) |  | [readonly] 
**PrimaryIp4** | [**NestedIPAddress**](NestedIPAddress.md) |  | [optional] 
**PrimaryIp6** | [**NestedIPAddress**](NestedIPAddress.md) |  | [optional] 
**Vcpus** | **Double** |  | [optional] 
**Memory** | **Int32** |  | [optional] 
**Disk** | **Int32** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**ConfigTemplate** | [**NestedConfigTemplate**](NestedConfigTemplate.md) |  | [optional] 
**LocalContextData** | [**AnyType**](.md) | Local config context data takes precedence over source contexts in the final rendered config context | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**ConfigContext** | [**AnyType**](.md) |  | [readonly] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**InterfaceCount** | **Int32** |  | [readonly] 
**VirtualDiskCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$VirtualMachineWithConfigContext = Initialize-PSOpenAPIToolsVirtualMachineWithConfigContext  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Status null `
 -Site null `
 -Cluster null `
 -Device null `
 -Role null `
 -Tenant null `
 -Platform null `
 -PrimaryIp null `
 -PrimaryIp4 null `
 -PrimaryIp6 null `
 -Vcpus null `
 -Memory null `
 -Disk null `
 -Description null `
 -Comments null `
 -ConfigTemplate null `
 -LocalContextData null `
 -Tags null `
 -CustomFields null `
 -ConfigContext null `
 -Created null `
 -LastUpdated null `
 -InterfaceCount null `
 -VirtualDiskCount null
```

- Convert the resource to JSON
```powershell
$VirtualMachineWithConfigContext | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

