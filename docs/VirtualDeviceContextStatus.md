# VirtualDeviceContextStatus
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;active&#x60; - Active * &#x60;planned&#x60; - Planned * &#x60;offline&#x60; - Offline | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$VirtualDeviceContextStatus = Initialize-PSOpenAPIToolsVirtualDeviceContextStatus  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$VirtualDeviceContextStatus | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

