# PowerFeedType
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;primary&#x60; - Primary * &#x60;redundant&#x60; - Redundant | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PowerFeedType = Initialize-PSOpenAPIToolsPowerFeedType  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$PowerFeedType | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

