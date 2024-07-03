# WritableASNRangeRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Rir** | **Int32** |  | 
**Start** | **Int64** |  | 
**VarEnd** | **Int64** |  | 
**Tenant** | **Int32** |  | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableASNRangeRequest = Initialize-PSOpenAPIToolsWritableASNRangeRequest  -Name null `
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
$WritableASNRangeRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

