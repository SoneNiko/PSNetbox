# DeviceTypeAirflow
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;front-to-rear&#x60; - Front to rear * &#x60;rear-to-front&#x60; - Rear to front * &#x60;left-to-right&#x60; - Left to right * &#x60;right-to-left&#x60; - Right to left * &#x60;side-to-rear&#x60; - Side to rear * &#x60;passive&#x60; - Passive * &#x60;mixed&#x60; - Mixed | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$DeviceTypeAirflow = Initialize-PSOpenAPIToolsDeviceTypeAirflow  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$DeviceTypeAirflow | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

