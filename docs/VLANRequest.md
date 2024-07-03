# VLANRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Site** | [**NestedSiteRequest**](NestedSiteRequest.md) |  | [optional] 
**Group** | [**NestedVLANGroupRequest**](NestedVLANGroupRequest.md) |  | [optional] 
**Vid** | **Int32** | Numeric VLAN ID (1-4094) | 
**Name** | **String** |  | 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**Status** | **String** | * &#x60;active&#x60; - Active * &#x60;reserved&#x60; - Reserved * &#x60;deprecated&#x60; - Deprecated | [optional] 
**Role** | [**NestedRoleRequest**](NestedRoleRequest.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$VLANRequest = Initialize-PSOpenAPIToolsVLANRequest  -Site null `
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
$VLANRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

