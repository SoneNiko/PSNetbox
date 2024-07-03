# CableLengthUnit
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;km&#x60; - Kilometers * &#x60;m&#x60; - Meters * &#x60;cm&#x60; - Centimeters * &#x60;mi&#x60; - Miles * &#x60;ft&#x60; - Feet * &#x60;in&#x60; - Inches | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$CableLengthUnit = Initialize-PSOpenAPIToolsCableLengthUnit  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$CableLengthUnit | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

