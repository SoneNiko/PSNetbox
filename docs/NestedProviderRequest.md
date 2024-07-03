# NestedProviderRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** | Full name of the provider | 
**Slug** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$NestedProviderRequest = Initialize-PSOpenAPIToolsNestedProviderRequest  -Name null `
 -Slug null
```

- Convert the resource to JSON
```powershell
$NestedProviderRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

