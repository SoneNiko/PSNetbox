# NestedVirtualChassisRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Master** | [**NestedDeviceRequest**](NestedDeviceRequest.md) |  | 

## Examples

- Prepare the resource
```powershell
$NestedVirtualChassisRequest = Initialize-PSOpenAPIToolsNestedVirtualChassisRequest  -Name null `
 -Master null
```

- Convert the resource to JSON
```powershell
$NestedVirtualChassisRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

