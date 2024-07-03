# WritableIPRangeRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StartAddress** | **String** |  | 
**EndAddress** | **String** |  | 
**Vrf** | **Int32** |  | [optional] 
**Tenant** | **Int32** |  | [optional] 
**Status** | **String** | Operational status of this range  * &#x60;active&#x60; - Active * &#x60;reserved&#x60; - Reserved * &#x60;deprecated&#x60; - Deprecated | [optional] 
**Role** | **Int32** | The primary function of this range | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**MarkUtilized** | **Boolean** | Treat as fully utilized | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableIPRangeRequest = Initialize-PSOpenAPIToolsWritableIPRangeRequest  -StartAddress null `
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
$WritableIPRangeRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

