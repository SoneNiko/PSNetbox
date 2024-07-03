# CustomFieldUiVisible
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;always&#x60; - Always * &#x60;if-set&#x60; - If set * &#x60;hidden&#x60; - Hidden | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$CustomFieldUiVisible = Initialize-PSOpenAPIToolsCustomFieldUiVisible  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$CustomFieldUiVisible | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

