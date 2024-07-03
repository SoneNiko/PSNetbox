# AggregateRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Prefix** | **String** |  | 
**Rir** | [**NestedRIRRequest**](NestedRIRRequest.md) |  | 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**DateAdded** | **System.DateTime** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$AggregateRequest = Initialize-PSOpenAPIToolsAggregateRequest  -Prefix null `
 -Rir null `
 -Tenant null `
 -DateAdded null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$AggregateRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

