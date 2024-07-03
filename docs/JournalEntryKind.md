# JournalEntryKind
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;info&#x60; - Info * &#x60;success&#x60; - Success * &#x60;warning&#x60; - Warning * &#x60;danger&#x60; - Danger | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$JournalEntryKind = Initialize-PSOpenAPIToolsJournalEntryKind  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$JournalEntryKind | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

