# JobStatus
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;pending&#x60; - Pending * &#x60;scheduled&#x60; - Scheduled * &#x60;running&#x60; - Running * &#x60;completed&#x60; - Completed * &#x60;errored&#x60; - Errored * &#x60;failed&#x60; - Failed | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$JobStatus = Initialize-PSOpenAPIToolsJobStatus  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$JobStatus | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

