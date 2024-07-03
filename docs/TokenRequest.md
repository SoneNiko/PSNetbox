# TokenRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**User** | [**NestedUserRequest**](NestedUserRequest.md) |  | 
**Expires** | **System.DateTime** |  | [optional] 
**LastUsed** | **System.DateTime** |  | [optional] 
**Key** | **String** |  | [optional] 
**WriteEnabled** | **Boolean** | Permit create/update/delete operations using this key | [optional] 
**Description** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$TokenRequest = Initialize-PSOpenAPIToolsTokenRequest  -User null `
 -Expires null `
 -LastUsed null `
 -Key null `
 -WriteEnabled null `
 -Description null
```

- Convert the resource to JSON
```powershell
$TokenRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

