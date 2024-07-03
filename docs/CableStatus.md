# CableStatus
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;connected&#x60; - Connected * &#x60;planned&#x60; - Planned * &#x60;decommissioning&#x60; - Decommissioning | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$CableStatus = Initialize-PSOpenAPIToolsCableStatus  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$CableStatus | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

