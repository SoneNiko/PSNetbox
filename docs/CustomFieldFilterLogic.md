# CustomFieldFilterLogic
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;disabled&#x60; - Disabled * &#x60;loose&#x60; - Loose * &#x60;exact&#x60; - Exact | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$CustomFieldFilterLogic = Initialize-PSOpenAPIToolsCustomFieldFilterLogic  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$CustomFieldFilterLogic | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

