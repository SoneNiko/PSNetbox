# JournalEntry
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**AssignedObjectType** | **String** |  | 
**AssignedObjectId** | **Int64** |  | 
**AssignedObject** | [**AnyType**](.md) |  | [readonly] 
**Created** | **System.DateTime** |  | [readonly] 
**CreatedBy** | **Int32** |  | [optional] 
**Kind** | [**JournalEntryKind**](JournalEntryKind.md) |  | [optional] 
**Comments** | **String** |  | 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$JournalEntry = Initialize-PSOpenAPIToolsJournalEntry  -Id null `
 -Url null `
 -Display null `
 -AssignedObjectType null `
 -AssignedObjectId null `
 -AssignedObject null `
 -Created null `
 -CreatedBy null `
 -Kind null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$JournalEntry | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

