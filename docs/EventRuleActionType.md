# EventRuleActionType
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;webhook&#x60; - Webhook * &#x60;script&#x60; - Script | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$EventRuleActionType = Initialize-PSOpenAPIToolsEventRuleActionType  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$EventRuleActionType | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

