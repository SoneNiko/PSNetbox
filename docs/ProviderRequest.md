# ProviderRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** | Full name of the provider | 
**Slug** | **String** |  | 
**Accounts** | **Int32[]** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Asns** | **Int32[]** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$ProviderRequest = Initialize-PSOpenAPIToolsProviderRequest  -Name null `
 -Slug null `
 -Accounts null `
 -Description null `
 -Comments null `
 -Asns null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$ProviderRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

