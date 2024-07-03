# ASNRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Asn** | **Int64** | 16- or 32-bit autonomous system number | 
**Rir** | [**NestedRIRRequest**](NestedRIRRequest.md) |  | [optional] 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$ASNRequest = Initialize-PSOpenAPIToolsASNRequest  -Asn null `
 -Rir null `
 -Tenant null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$ASNRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

