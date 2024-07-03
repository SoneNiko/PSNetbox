# TunnelTerminationRole
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;peer&#x60; - Peer * &#x60;hub&#x60; - Hub * &#x60;spoke&#x60; - Spoke | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$TunnelTerminationRole = Initialize-PSOpenAPIToolsTunnelTerminationRole  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$TunnelTerminationRole | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

