# PatchedWritableJournalEntryRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssignedObjectType** | **String** |  | [optional] 
**AssignedObjectId** | **Int64** |  | [optional] 
**CreatedBy** | **Int32** |  | [optional] 
**Kind** | **String** | * &#x60;info&#x60; - Info * &#x60;success&#x60; - Success * &#x60;warning&#x60; - Warning * &#x60;danger&#x60; - Danger | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableJournalEntryRequest = Initialize-PSOpenAPIToolsPatchedWritableJournalEntryRequest  -AssignedObjectType null `
 -AssignedObjectId null `
 -CreatedBy null `
 -Kind null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableJournalEntryRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

