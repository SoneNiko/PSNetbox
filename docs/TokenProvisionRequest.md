# TokenProvisionRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Expires** | **System.DateTime** |  | [optional] 
**WriteEnabled** | **Boolean** | Permit create/update/delete operations using this key | [optional] 
**Description** | **String** |  | [optional] 
**Username** | **String** |  | 
**Password** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$TokenProvisionRequest = Initialize-PSOpenAPIToolsTokenProvisionRequest  -Expires null `
 -WriteEnabled null `
 -Description null `
 -Username null `
 -Password null
```

- Convert the resource to JSON
```powershell
$TokenProvisionRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

