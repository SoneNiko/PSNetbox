# PatchedWritableContactAssignmentRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentType** | **String** |  | [optional] 
**ObjectId** | **Int64** |  | [optional] 
**Contact** | **Int32** |  | [optional] 
**Role** | **Int32** |  | [optional] 
**Priority** | **String** | * &#x60;primary&#x60; - Primary * &#x60;secondary&#x60; - Secondary * &#x60;tertiary&#x60; - Tertiary * &#x60;inactive&#x60; - Inactive | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableContactAssignmentRequest = Initialize-PSOpenAPIToolsPatchedWritableContactAssignmentRequest  -ContentType null `
 -ObjectId null `
 -Contact null `
 -Role null `
 -Priority null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableContactAssignmentRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

