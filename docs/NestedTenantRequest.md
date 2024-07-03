# NestedTenantRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Slug** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$NestedTenantRequest = Initialize-PSOpenAPIToolsNestedTenantRequest  -Name null `
 -Slug null
```

- Convert the resource to JSON
```powershell
$NestedTenantRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

