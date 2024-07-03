# CircuitStatus
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;planned&#x60; - Planned * &#x60;provisioning&#x60; - Provisioning * &#x60;active&#x60; - Active * &#x60;offline&#x60; - Offline * &#x60;deprovisioning&#x60; - Deprovisioning * &#x60;decommissioned&#x60; - Decommissioned | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$CircuitStatus = Initialize-PSOpenAPIToolsCircuitStatus  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$CircuitStatus | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

