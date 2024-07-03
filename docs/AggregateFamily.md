# AggregateFamily
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **Int32** | * &#x60;4&#x60; - IPv4 * &#x60;6&#x60; - IPv6 | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$AggregateFamily = Initialize-PSOpenAPIToolsAggregateFamily  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$AggregateFamily | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

