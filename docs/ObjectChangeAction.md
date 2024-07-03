# ObjectChangeAction
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;create&#x60; - Created * &#x60;update&#x60; - Updated * &#x60;delete&#x60; - Deleted | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$ObjectChangeAction = Initialize-PSOpenAPIToolsObjectChangeAction  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$ObjectChangeAction | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

