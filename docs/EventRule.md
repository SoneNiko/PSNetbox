# EventRule
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**ContentTypes** | **String[]** |  | 
**Name** | **String** |  | 
**TypeCreate** | **Boolean** | Triggers when a matching object is created. | [optional] 
**TypeUpdate** | **Boolean** | Triggers when a matching object is updated. | [optional] 
**TypeDelete** | **Boolean** | Triggers when a matching object is deleted. | [optional] 
**TypeJobStart** | **Boolean** | Triggers when a job for a matching object is started. | [optional] 
**TypeJobEnd** | **Boolean** | Triggers when a job for a matching object terminates. | [optional] 
**Enabled** | **Boolean** |  | [optional] 
**Conditions** | [**AnyType**](.md) | A set of conditions which determine whether the event will be generated. | [optional] 
**ActionType** | [**EventRuleActionType**](EventRuleActionType.md) |  | 
**ActionObjectType** | **String** |  | 
**ActionObjectId** | **Int64** |  | [optional] 
**ActionObject** | [**System.Collections.Hashtable**](AnyType.md) |  | [readonly] 
**Description** | **String** |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$EventRule = Initialize-PSOpenAPIToolsEventRule  -Id null `
 -Url null `
 -Display null `
 -ContentTypes null `
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
 -ActionObject null `
 -Description null `
 -CustomFields null `
 -Tags null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$EventRule | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

