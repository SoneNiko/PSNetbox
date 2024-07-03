# CableTerminationRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cable** | **Int32** |  | 
**CableEnd** | **String** | * &#x60;A&#x60; - A * &#x60;B&#x60; - B | 
**TerminationType** | **String** |  | 
**TerminationId** | **Int64** |  | 

## Examples

- Prepare the resource
```powershell
$CableTerminationRequest = Initialize-PSOpenAPIToolsCableTerminationRequest  -Cable null `
 -CableEnd null `
 -TerminationType null `
 -TerminationId null
```

- Convert the resource to JSON
```powershell
$CableTerminationRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

