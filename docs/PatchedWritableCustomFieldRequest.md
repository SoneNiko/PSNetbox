# PatchedWritableCustomFieldRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentTypes** | **String[]** |  | [optional] 
**Type** | **String** | The type of data this custom field holds  * &#x60;text&#x60; - Text * &#x60;longtext&#x60; - Text (long) * &#x60;integer&#x60; - Integer * &#x60;decimal&#x60; - Decimal * &#x60;boolean&#x60; - Boolean (true/false) * &#x60;date&#x60; - Date * &#x60;datetime&#x60; - Date &amp; time * &#x60;url&#x60; - URL * &#x60;json&#x60; - JSON * &#x60;select&#x60; - Selection * &#x60;multiselect&#x60; - Multiple selection * &#x60;object&#x60; - Object * &#x60;multiobject&#x60; - Multiple objects | [optional] 
**ObjectType** | **String** |  | [optional] 
**Name** | **String** | Internal field name | [optional] 
**Label** | **String** | Name of the field as displayed to users (if not provided, &#39;the field&#39;s name will be used) | [optional] 
**GroupName** | **String** | Custom fields within the same group will be displayed together | [optional] 
**Description** | **String** |  | [optional] 
**Required** | **Boolean** | If true, this field is required when creating new objects or editing an existing object. | [optional] 
**SearchWeight** | **Int32** | Weighting for search. Lower values are considered more important. Fields with a search weight of zero will be ignored. | [optional] 
**FilterLogic** | **String** | Loose matches any instance of a given string; exact matches the entire field.  * &#x60;disabled&#x60; - Disabled * &#x60;loose&#x60; - Loose * &#x60;exact&#x60; - Exact | [optional] 
**UiVisible** | **String** | Specifies whether the custom field is displayed in the UI  * &#x60;always&#x60; - Always * &#x60;if-set&#x60; - If set * &#x60;hidden&#x60; - Hidden | [optional] 
**UiEditable** | **String** | Specifies whether the custom field value can be edited in the UI  * &#x60;yes&#x60; - Yes * &#x60;no&#x60; - No * &#x60;hidden&#x60; - Hidden | [optional] 
**IsCloneable** | **Boolean** | Replicate this value when cloning objects | [optional] 
**Default** | [**AnyType**](.md) | Default value for the field (must be a JSON value). Encapsulate strings with double quotes (e.g. &quot;&quot;Foo&quot;&quot;). | [optional] 
**Weight** | **Int32** | Fields with higher weights appear lower in a form. | [optional] 
**ValidationMinimum** | **Int64** | Minimum allowed value (for numeric fields) | [optional] 
**ValidationMaximum** | **Int64** | Maximum allowed value (for numeric fields) | [optional] 
**ValidationRegex** | **String** | Regular expression to enforce on text field values. Use ^ and $ to force matching of entire string. For example, &lt;code&gt;^[A-Z]{3}$&lt;/code&gt; will limit values to exactly three uppercase letters. | [optional] 
**ChoiceSet** | **Int32** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableCustomFieldRequest = Initialize-PSOpenAPIToolsPatchedWritableCustomFieldRequest  -ContentTypes null `
 -Type null `
 -ObjectType null `
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
 -ChoiceSet null
```

- Convert the resource to JSON
```powershell
$PatchedWritableCustomFieldRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

