# PatchedWritableBookmarkRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ObjectType** | **String** |  | [optional] 
**ObjectId** | **Int64** |  | [optional] 
**User** | **Int32** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableBookmarkRequest = Initialize-PSOpenAPIToolsPatchedWritableBookmarkRequest  -ObjectType null `
 -ObjectId null `
 -User null
```

- Convert the resource to JSON
```powershell
$PatchedWritableBookmarkRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

