# PatchedWritableVirtualDeviceContextRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | [optional] 
**Device** | **Int32** |  | [optional] 
**Identifier** | **Int32** | Numeric identifier unique to the parent device | [optional] 
**Tenant** | **Int32** |  | [optional] 
**PrimaryIp4** | **Int32** |  | [optional] 
**PrimaryIp6** | **Int32** |  | [optional] 
**Status** | **String** | * &#x60;active&#x60; - Active * &#x60;planned&#x60; - Planned * &#x60;offline&#x60; - Offline | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableVirtualDeviceContextRequest = Initialize-PSOpenAPIToolsPatchedWritableVirtualDeviceContextRequest  -Name null `
 -Device null `
 -Identifier null `
 -Tenant null `
 -PrimaryIp4 null `
 -PrimaryIp6 null `
 -Status null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableVirtualDeviceContextRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

