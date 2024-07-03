# NestedUserRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Username** | **String** | Required. 150 characters or fewer. Letters, digits and @/./+/-/_ only. | 

## Examples

- Prepare the resource
```powershell
$NestedUserRequest = Initialize-PSOpenAPIToolsNestedUserRequest  -Username null
```

- Convert the resource to JSON
```powershell
$NestedUserRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

