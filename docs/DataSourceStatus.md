# DataSourceStatus
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;new&#x60; - New * &#x60;queued&#x60; - Queued * &#x60;syncing&#x60; - Syncing * &#x60;completed&#x60; - Completed * &#x60;failed&#x60; - Failed | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$DataSourceStatus = Initialize-PSOpenAPIToolsDataSourceStatus  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$DataSourceStatus | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

