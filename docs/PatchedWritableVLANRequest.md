# PatchedWritableVLANRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Site** | **Int32** | The specific site to which this VLAN is assigned (if any) | [optional] 
**Group** | **Int32** | VLAN group (optional) | [optional] 
**Vid** | **Int32** | Numeric VLAN ID (1-4094) | [optional] 
**Name** | **String** |  | [optional] 
**Tenant** | **Int32** |  | [optional] 
**Status** | **String** | Operational status of this VLAN  * &#x60;active&#x60; - Active * &#x60;reserved&#x60; - Reserved * &#x60;deprecated&#x60; - Deprecated | [optional] 
**Role** | **Int32** | The primary function of this VLAN | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableVLANRequest = Initialize-PSOpenAPIToolsPatchedWritableVLANRequest  -Site null `
 -Group null `
 -Vid null `
 -Name null `
 -Tenant null `
 -Status null `
 -Role null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableVLANRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

