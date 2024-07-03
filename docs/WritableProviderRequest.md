# WritableProviderRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** | Full name of the provider | 
**Slug** | **String** |  | 
**Accounts** | **Int32[]** |  | 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Asns** | **Int32[]** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableProviderRequest = Initialize-PSOpenAPIToolsWritableProviderRequest  -Name null `
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
$WritableProviderRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

