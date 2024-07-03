# TagRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Color** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**ObjectTypes** | **String[]** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$TagRequest = Initialize-PSOpenAPIToolsTagRequest  -Name null `
 -Slug null `
 -Color null `
 -Description null `
 -ObjectTypes null
```

- Convert the resource to JSON
```powershell
$TagRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

