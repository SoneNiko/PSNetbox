# DeviceBayRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Device** | [**NestedDeviceRequest**](NestedDeviceRequest.md) |  | 
**Name** | **String** |  | 
**Label** | **String** | Physical label | [optional] 
**Description** | **String** |  | [optional] 
**InstalledDevice** | [**NestedDeviceRequest**](NestedDeviceRequest.md) |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$DeviceBayRequest = Initialize-PSOpenAPIToolsDeviceBayRequest  -Device null `
 -Name null `
 -Label null `
 -Description null `
 -InstalledDevice null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$DeviceBayRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

