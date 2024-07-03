# ContactAssignment
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**ContentType** | **String** |  | 
**ObjectId** | **Int64** |  | 
**Object** | [**System.Collections.Hashtable**](AnyType.md) |  | [readonly] 
**Contact** | [**NestedContact**](NestedContact.md) |  | 
**Role** | [**NestedContactRole**](NestedContactRole.md) |  | [optional] 
**Priority** | [**ContactAssignmentPriority**](ContactAssignmentPriority.md) |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$ContactAssignment = Initialize-PSOpenAPIToolsContactAssignment  -Id null `
 -Url null `
 -Display null `
 -ContentType null `
 -ObjectId null `
 -Object null `
 -Contact null `
 -Role null `
 -Priority null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$ContactAssignment | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

