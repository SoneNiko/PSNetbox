# PatchedWritableVirtualMachineWithConfigContextRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | [optional] 
**Status** | **String** | * &#x60;offline&#x60; - Offline * &#x60;active&#x60; - Active * &#x60;planned&#x60; - Planned * &#x60;staged&#x60; - Staged * &#x60;failed&#x60; - Failed * &#x60;decommissioning&#x60; - Decommissioning | [optional] 
**Site** | **Int32** |  | [optional] 
**Cluster** | **Int32** |  | [optional] 
**Device** | **Int32** |  | [optional] 
**Role** | **Int32** |  | [optional] 
**Tenant** | **Int32** |  | [optional] 
**Platform** | **Int32** |  | [optional] 
**PrimaryIp4** | **Int32** |  | [optional] 
**PrimaryIp6** | **Int32** |  | [optional] 
**Vcpus** | **Double** |  | [optional] 
**Memory** | **Int32** |  | [optional] 
**Disk** | **Int32** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**ConfigTemplate** | **Int32** |  | [optional] 
**LocalContextData** | [**AnyType**](.md) | Local config context data takes precedence over source contexts in the final rendered config context | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableVirtualMachineWithConfigContextRequest = Initialize-PSOpenAPIToolsPatchedWritableVirtualMachineWithConfigContextRequest  -Name null `
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
$PatchedWritableVirtualMachineWithConfigContextRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

