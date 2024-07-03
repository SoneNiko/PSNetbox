# PatchedWritableCustomFieldChoiceSetRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**BaseChoices** | **String** | Base set of predefined choices (optional)  * &#x60;IATA&#x60; - IATA (Airport codes) * &#x60;ISO_3166&#x60; - ISO 3166 (Country codes) * &#x60;UN_LOCODE&#x60; - UN/LOCODE (Location codes) | [optional] 
**ExtraChoices** | [**AnyType[][]**](Array.md) |  | [optional] 
**OrderAlphabetically** | **Boolean** | Choices are automatically ordered alphabetically | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableCustomFieldChoiceSetRequest = Initialize-PSOpenAPIToolsPatchedWritableCustomFieldChoiceSetRequest  -Name null `
 -Description null `
 -BaseChoices null `
 -ExtraChoices null `
 -OrderAlphabetically null
```

- Convert the resource to JSON
```powershell
$PatchedWritableCustomFieldChoiceSetRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

