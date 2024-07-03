# LocationStatus
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;planned&#x60; - Planned * &#x60;staging&#x60; - Staging * &#x60;active&#x60; - Active * &#x60;decommissioning&#x60; - Decommissioning * &#x60;retired&#x60; - Retired | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$LocationStatus = Initialize-PSOpenAPIToolsLocationStatus  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$LocationStatus | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

