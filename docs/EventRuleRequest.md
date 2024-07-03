# EventRuleRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentTypes** | **String[]** |  | 
**Name** | **String** |  | 
**TypeCreate** | **Boolean** | Triggers when a matching object is created. | [optional] 
**TypeUpdate** | **Boolean** | Triggers when a matching object is updated. | [optional] 
**TypeDelete** | **Boolean** | Triggers when a matching object is deleted. | [optional] 
**TypeJobStart** | **Boolean** | Triggers when a job for a matching object is started. | [optional] 
**TypeJobEnd** | **Boolean** | Triggers when a job for a matching object terminates. | [optional] 
**Enabled** | **Boolean** |  | [optional] 
**Conditions** | [**AnyType**](.md) | A set of conditions which determine whether the event will be generated. | [optional] 
**ActionType** | **String** | * &#x60;webhook&#x60; - Webhook * &#x60;script&#x60; - Script | 
**ActionObjectType** | **String** |  | 
**ActionObjectId** | **Int64** |  | [optional] 
**Description** | **String** |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$EventRuleRequest = Initialize-PSOpenAPIToolsEventRuleRequest  -ContentTypes null `
 -Name null `
 -TypeCreate null `
 -TypeUpdate null `
 -TypeDelete null `
 -TypeJobStart null `
 -TypeJobEnd null `
 -Enabled null `
 -Conditions null `
 -ActionType null `
 -ActionObjectType null `
 -ActionObjectId null `
 -Description null `
 -CustomFields null `
 -Tags null
```

- Convert the resource to JSON
```powershell
$EventRuleRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

