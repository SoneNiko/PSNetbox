# IPRangeRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StartAddress** | **String** |  | 
**EndAddress** | **String** |  | 
**Vrf** | [**NestedVRFRequest**](NestedVRFRequest.md) |  | [optional] 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**Status** | **String** | * &#x60;active&#x60; - Active * &#x60;reserved&#x60; - Reserved * &#x60;deprecated&#x60; - Deprecated | [optional] 
**Role** | [**NestedRoleRequest**](NestedRoleRequest.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**MarkUtilized** | **Boolean** | Treat as fully utilized | [optional] 

## Examples

- Prepare the resource
```powershell
$IPRangeRequest = Initialize-PSOpenAPIToolsIPRangeRequest  -StartAddress null `
 -EndAddress null `
 -Vrf null `
 -Tenant null `
 -Status null `
 -Role null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -MarkUtilized null
```

- Convert the resource to JSON
```powershell
$IPRangeRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

