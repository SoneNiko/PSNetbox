# WritablePrefixRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Prefix** | **String** |  | 
**Site** | **Int32** |  | [optional] 
**Vrf** | **Int32** |  | [optional] 
**Tenant** | **Int32** |  | [optional] 
**Vlan** | **Int32** |  | [optional] 
**Status** | **String** | Operational status of this prefix  * &#x60;container&#x60; - Container * &#x60;active&#x60; - Active * &#x60;reserved&#x60; - Reserved * &#x60;deprecated&#x60; - Deprecated | [optional] 
**Role** | **Int32** | The primary function of this prefix | [optional] 
**IsPool** | **Boolean** | All IP addresses within this prefix are considered usable | [optional] 
**MarkUtilized** | **Boolean** | Treat as fully utilized | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritablePrefixRequest = Initialize-PSOpenAPIToolsWritablePrefixRequest  -Prefix null `
 -Site null `
 -Vrf null `
 -Tenant null `
 -Vlan null `
 -Status null `
 -Role null `
 -IsPool null `
 -MarkUtilized null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$WritablePrefixRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

