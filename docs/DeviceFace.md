# DeviceFace
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;front&#x60; - Front * &#x60;rear&#x60; - Rear | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$DeviceFace = Initialize-PSOpenAPIToolsDeviceFace  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$DeviceFace | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

