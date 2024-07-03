# ClusterStatus
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;planned&#x60; - Planned * &#x60;staging&#x60; - Staging * &#x60;active&#x60; - Active * &#x60;decommissioning&#x60; - Decommissioning * &#x60;offline&#x60; - Offline | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$ClusterStatus = Initialize-PSOpenAPIToolsClusterStatus  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$ClusterStatus | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

