# CustomFieldChoiceSetRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**BaseChoices** | **String** | * &#x60;IATA&#x60; - IATA (Airport codes) * &#x60;ISO_3166&#x60; - ISO 3166 (Country codes) * &#x60;UN_LOCODE&#x60; - UN/LOCODE (Location codes) | [optional] 
**ExtraChoices** | [**AnyType[][]**](Array.md) |  | 
**OrderAlphabetically** | **Boolean** | Choices are automatically ordered alphabetically | [optional] 

## Examples

- Prepare the resource
```powershell
$CustomFieldChoiceSetRequest = Initialize-PSOpenAPIToolsCustomFieldChoiceSetRequest  -Name null `
 -Description null `
 -BaseChoices null `
 -ExtraChoices null `
 -OrderAlphabetically null
```

- Convert the resource to JSON
```powershell
$CustomFieldChoiceSetRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

