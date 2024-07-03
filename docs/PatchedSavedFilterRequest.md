# PatchedSavedFilterRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentTypes** | **String[]** |  | [optional] 
**Name** | **String** |  | [optional] 
**Slug** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**User** | **Int32** |  | [optional] 
**Weight** | **Int32** |  | [optional] 
**Enabled** | **Boolean** |  | [optional] 
**Shared** | **Boolean** |  | [optional] 
**Parameters** | [**AnyType**](.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedSavedFilterRequest = Initialize-PSOpenAPIToolsPatchedSavedFilterRequest  -ContentTypes null `
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
$PatchedSavedFilterRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

