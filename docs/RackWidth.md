# RackWidth
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **Int32** | * &#x60;10&#x60; - 10 inches * &#x60;19&#x60; - 19 inches * &#x60;21&#x60; - 21 inches * &#x60;23&#x60; - 23 inches | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$RackWidth = Initialize-PSOpenAPIToolsRackWidth  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$RackWidth | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

