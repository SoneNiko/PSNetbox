# CustomField
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**ContentTypes** | **String[]** |  | 
**Type** | [**CustomFieldType**](CustomFieldType.md) |  | 
**ObjectType** | **String** |  | [optional] 
**DataType** | **String** |  | [readonly] 
**Name** | **String** | Internal field name | 
**Label** | **String** | Name of the field as displayed to users (if not provided, &#39;the field&#39;s name will be used) | [optional] 
**GroupName** | **String** | Custom fields within the same group will be displayed together | [optional] 
**Description** | **String** |  | [optional] 
**Required** | **Boolean** | If true, this field is required when creating new objects or editing an existing object. | [optional] 
**SearchWeight** | **Int32** | Weighting for search. Lower values are considered more important. Fields with a search weight of zero will be ignored. | [optional] 
**FilterLogic** | [**CustomFieldFilterLogic**](CustomFieldFilterLogic.md) |  | [optional] 
**UiVisible** | [**CustomFieldUiVisible**](CustomFieldUiVisible.md) |  | [optional] 
**UiEditable** | [**CustomFieldUiEditable**](CustomFieldUiEditable.md) |  | [optional] 
**IsCloneable** | **Boolean** | Replicate this value when cloning objects | [optional] 
**Default** | [**AnyType**](.md) | Default value for the field (must be a JSON value). Encapsulate strings with double quotes (e.g. &quot;&quot;Foo&quot;&quot;). | [optional] 
**Weight** | **Int32** | Fields with higher weights appear lower in a form. | [optional] 
**ValidationMinimum** | **Int64** | Minimum allowed value (for numeric fields) | [optional] 
**ValidationMaximum** | **Int64** | Maximum allowed value (for numeric fields) | [optional] 
**ValidationRegex** | **String** | Regular expression to enforce on text field values. Use ^ and $ to force matching of entire string. For example, &lt;code&gt;^[A-Z]{3}$&lt;/code&gt; will limit values to exactly three uppercase letters. | [optional] 
**ChoiceSet** | [**NestedCustomFieldChoiceSet**](NestedCustomFieldChoiceSet.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$CustomField = Initialize-PSOpenAPIToolsCustomField  -Id null `
 -Url null `
 -Display null `
 -ContentTypes null `
 -Type null `
 -ObjectType null `
 -DataType null `
 -Name null `
 -Label null `
 -GroupName null `
 -Description null `
 -Required null `
 -SearchWeight null `
 -FilterLogic null `
 -UiVisible null `
 -UiEditable null `
 -IsCloneable null `
 -Default null `
 -Weight null `
 -ValidationMinimum null `
 -ValidationMaximum null `
 -ValidationRegex null `
 -ChoiceSet null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$CustomField | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

