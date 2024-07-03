# BookmarkRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ObjectType** | **String** |  | 
**ObjectId** | **Int64** |  | 
**User** | [**NestedUserRequest**](NestedUserRequest.md) |  | 

## Examples

- Prepare the resource
```powershell
$BookmarkRequest = Initialize-PSOpenAPIToolsBookmarkRequest  -ObjectType null `
 -ObjectId null `
 -User null
```

- Convert the resource to JSON
```powershell
$BookmarkRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

