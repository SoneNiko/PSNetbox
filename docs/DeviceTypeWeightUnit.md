# DeviceTypeWeightUnit
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;kg&#x60; - Kilograms * &#x60;g&#x60; - Grams * &#x60;lb&#x60; - Pounds * &#x60;oz&#x60; - Ounces | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$DeviceTypeWeightUnit = Initialize-PSOpenAPIToolsDeviceTypeWeightUnit  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$DeviceTypeWeightUnit | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

