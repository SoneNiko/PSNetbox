# InterfaceMode
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;access&#x60; - Access * &#x60;tagged&#x60; - Tagged * &#x60;tagged-all&#x60; - Tagged (All) | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$InterfaceMode = Initialize-PSOpenAPIToolsInterfaceMode  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$InterfaceMode | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

