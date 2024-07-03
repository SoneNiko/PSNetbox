# FrontPortRearPortRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Label** | **String** | Physical label | [optional] 
**Description** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$FrontPortRearPortRequest = Initialize-PSOpenAPIToolsFrontPortRearPortRequest  -Name null `
 -Label null `
 -Description null
```

- Convert the resource to JSON
```powershell
$FrontPortRearPortRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

