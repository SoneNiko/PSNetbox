# NestedSiteRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** | Full name of the site | 
**Slug** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$NestedSiteRequest = Initialize-PSOpenAPIToolsNestedSiteRequest  -Name null `
 -Slug null
```

- Convert the resource to JSON
```powershell
$NestedSiteRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

