# RackStatus
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;reserved&#x60; - Reserved * &#x60;available&#x60; - Available * &#x60;planned&#x60; - Planned * &#x60;active&#x60; - Active * &#x60;deprecated&#x60; - Deprecated | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$RackStatus = Initialize-PSOpenAPIToolsRackStatus  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$RackStatus | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

