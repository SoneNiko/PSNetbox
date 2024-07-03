# PatchedWritableAggregateRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Prefix** | **String** |  | [optional] 
**Rir** | **Int32** | Regional Internet Registry responsible for this IP space | [optional] 
**Tenant** | **Int32** |  | [optional] 
**DateAdded** | **System.DateTime** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableAggregateRequest = Initialize-PSOpenAPIToolsPatchedWritableAggregateRequest  -Prefix null `
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
$PatchedWritableAggregateRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

