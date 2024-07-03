# ASNRangeRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Rir** | [**NestedRIRRequest**](NestedRIRRequest.md) |  | 
**Start** | **Int64** |  | 
**VarEnd** | **Int64** |  | 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$ASNRangeRequest = Initialize-PSOpenAPIToolsASNRangeRequest  -Name null `
 -Slug null `
 -Rir null `
 -Start null `
 -VarEnd null `
 -Tenant null `
 -Description null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$ASNRangeRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

