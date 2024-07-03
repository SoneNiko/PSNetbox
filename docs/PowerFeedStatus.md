# PowerFeedStatus
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;offline&#x60; - Offline * &#x60;active&#x60; - Active * &#x60;planned&#x60; - Planned * &#x60;failed&#x60; - Failed | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PowerFeedStatus = Initialize-PSOpenAPIToolsPowerFeedStatus  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$PowerFeedStatus | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

