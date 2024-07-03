# WritableBookmarkRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ObjectType** | **String** |  | 
**ObjectId** | **Int64** |  | 
**User** | **Int32** |  | 

## Examples

- Prepare the resource
```powershell
$WritableBookmarkRequest = Initialize-PSOpenAPIToolsWritableBookmarkRequest  -ObjectType null `
 -ObjectId null `
 -User null
```

- Convert the resource to JSON
```powershell
$WritableBookmarkRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

