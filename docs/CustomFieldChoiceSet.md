# CustomFieldChoiceSet
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**BaseChoices** | [**CustomFieldChoiceSetBaseChoices**](CustomFieldChoiceSetBaseChoices.md) |  | [optional] 
**ExtraChoices** | [**AnyType[][]**](Array.md) |  | 
**OrderAlphabetically** | **Boolean** | Choices are automatically ordered alphabetically | [optional] 
**ChoicesCount** | **String** |  | [readonly] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$CustomFieldChoiceSet = Initialize-PSOpenAPIToolsCustomFieldChoiceSet  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Description null `
 -BaseChoices null `
 -ExtraChoices null `
 -OrderAlphabetically null `
 -ChoicesCount null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$CustomFieldChoiceSet | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

