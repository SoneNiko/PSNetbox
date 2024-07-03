# VirtualMachineWithConfigContextRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Status** | **String** | * &#x60;offline&#x60; - Offline * &#x60;active&#x60; - Active * &#x60;planned&#x60; - Planned * &#x60;staged&#x60; - Staged * &#x60;failed&#x60; - Failed * &#x60;decommissioning&#x60; - Decommissioning | [optional] 
**Site** | [**NestedSiteRequest**](NestedSiteRequest.md) |  | [optional] 
**Cluster** | [**NestedClusterRequest**](NestedClusterRequest.md) |  | [optional] 
**Device** | [**NestedDeviceRequest**](NestedDeviceRequest.md) |  | [optional] 
**Role** | [**NestedDeviceRoleRequest**](NestedDeviceRoleRequest.md) |  | [optional] 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**Platform** | [**NestedPlatformRequest**](NestedPlatformRequest.md) |  | [optional] 
**PrimaryIp4** | [**NestedIPAddressRequest**](NestedIPAddressRequest.md) |  | [optional] 
**PrimaryIp6** | [**NestedIPAddressRequest**](NestedIPAddressRequest.md) |  | [optional] 
**Vcpus** | **Double** |  | [optional] 
**Memory** | **Int32** |  | [optional] 
**Disk** | **Int32** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**ConfigTemplate** | [**NestedConfigTemplateRequest**](NestedConfigTemplateRequest.md) |  | [optional] 
**LocalContextData** | [**AnyType**](.md) | Local config context data takes precedence over source contexts in the final rendered config context | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$VirtualMachineWithConfigContextRequest = Initialize-PSOpenAPIToolsVirtualMachineWithConfigContextRequest  -Name null `
 -Status null `
 -Site null `
 -Cluster null `
 -Device null `
 -Role null `
 -Tenant null `
 -Platform null `
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
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$VirtualMachineWithConfigContextRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

