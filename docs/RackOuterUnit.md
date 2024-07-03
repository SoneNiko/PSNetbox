# RackOuterUnit
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;mm&#x60; - Millimeters * &#x60;in&#x60; - Inches | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$RackOuterUnit = Initialize-PSOpenAPIToolsRackOuterUnit  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$RackOuterUnit | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

