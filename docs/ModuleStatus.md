# ModuleStatus
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;offline&#x60; - Offline * &#x60;active&#x60; - Active * &#x60;planned&#x60; - Planned * &#x60;staged&#x60; - Staged * &#x60;failed&#x60; - Failed * &#x60;decommissioning&#x60; - Decommissioning | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$ModuleStatus = Initialize-PSOpenAPIToolsModuleStatus  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$ModuleStatus | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

