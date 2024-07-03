# PatchedImageAttachmentRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentType** | **String** |  | [optional] 
**ObjectId** | **Int64** |  | [optional] 
**Name** | **String** |  | [optional] 
**Image** | **System.IO.FileInfo** |  | [optional] 
**ImageHeight** | **Int32** |  | [optional] 
**ImageWidth** | **Int32** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedImageAttachmentRequest = Initialize-PSOpenAPIToolsPatchedImageAttachmentRequest  -ContentType null `
 -ObjectId null `
 -Name null `
 -Image null `
 -ImageHeight null `
 -ImageWidth null
```

- Convert the resource to JSON
```powershell
$PatchedImageAttachmentRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

