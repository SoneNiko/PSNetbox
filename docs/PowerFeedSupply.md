# PowerFeedSupply
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;ac&#x60; - AC * &#x60;dc&#x60; - DC | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PowerFeedSupply = Initialize-PSOpenAPIToolsPowerFeedSupply  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$PowerFeedSupply | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

