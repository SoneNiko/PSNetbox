# PatchedWritableASNRangeRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | [optional] 
**Slug** | **String** |  | [optional] 
**Rir** | **Int32** |  | [optional] 
**Start** | **Int64** |  | [optional] 
**VarEnd** | **Int64** |  | [optional] 
**Tenant** | **Int32** |  | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableASNRangeRequest = Initialize-PSOpenAPIToolsPatchedWritableASNRangeRequest  -Name null `
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
$PatchedWritableASNRangeRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

