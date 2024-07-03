# PatchedCableTerminationRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cable** | **Int32** |  | [optional] 
**CableEnd** | **String** | * &#x60;A&#x60; - A * &#x60;B&#x60; - B | [optional] 
**TerminationType** | **String** |  | [optional] 
**TerminationId** | **Int64** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedCableTerminationRequest = Initialize-PSOpenAPIToolsPatchedCableTerminationRequest  -Cable null `
 -CableEnd null `
 -TerminationType null `
 -TerminationId null
```

- Convert the resource to JSON
```powershell
$PatchedCableTerminationRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

