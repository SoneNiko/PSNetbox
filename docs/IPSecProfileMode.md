# IPSecProfileMode
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;esp&#x60; - ESP * &#x60;ah&#x60; - AH | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$IPSecProfileMode = Initialize-PSOpenAPIToolsIPSecProfileMode  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$IPSecProfileMode | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

