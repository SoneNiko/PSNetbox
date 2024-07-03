# PowerOutletFeedLeg
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;A&#x60; - A * &#x60;B&#x60; - B * &#x60;C&#x60; - C | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PowerOutletFeedLeg = Initialize-PSOpenAPIToolsPowerOutletFeedLeg  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$PowerOutletFeedLeg | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

