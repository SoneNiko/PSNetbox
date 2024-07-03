# PowerFeedPhase
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;single-phase&#x60; - Single phase * &#x60;three-phase&#x60; - Three-phase | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PowerFeedPhase = Initialize-PSOpenAPIToolsPowerFeedPhase  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$PowerFeedPhase | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

