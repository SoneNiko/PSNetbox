# SavedFilterRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentTypes** | **String[]** |  | 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Description** | **String** |  | [optional] 
**User** | **Int32** |  | [optional] 
**Weight** | **Int32** |  | [optional] 
**Enabled** | **Boolean** |  | [optional] 
**Shared** | **Boolean** |  | [optional] 
**Parameters** | [**AnyType**](.md) |  | 

## Examples

- Prepare the resource
```powershell
$SavedFilterRequest = Initialize-PSOpenAPIToolsSavedFilterRequest  -ContentTypes null `
 -Name null `
 -Slug null `
 -Description null `
 -User null `
 -Weight null `
 -Enabled null `
 -Shared null `
 -Parameters null
```

- Convert the resource to JSON
```powershell
$SavedFilterRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

