# Bookmark
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**ObjectType** | **String** |  | 
**ObjectId** | **Int64** |  | 
**Object** | [**AnyType**](.md) |  | [readonly] 
**User** | [**NestedUser**](NestedUser.md) |  | 
**Created** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Bookmark = Initialize-PSOpenAPIToolsBookmark  -Id null `
 -Url null `
 -Display null `
 -ObjectType null `
 -ObjectId null `
 -Object null `
 -User null `
 -Created null
```

- Convert the resource to JSON
```powershell
$Bookmark | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

