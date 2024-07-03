# ImageAttachmentRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentType** | **String** |  | 
**ObjectId** | **Int64** |  | 
**Name** | **String** |  | [optional] 
**Image** | **System.IO.FileInfo** |  | 
**ImageHeight** | **Int32** |  | 
**ImageWidth** | **Int32** |  | 

## Examples

- Prepare the resource
```powershell
$ImageAttachmentRequest = Initialize-PSOpenAPIToolsImageAttachmentRequest  -ContentType null `
 -ObjectId null `
 -Name null `
 -Image null `
 -ImageHeight null `
 -ImageWidth null
```

- Convert the resource to JSON
```powershell
$ImageAttachmentRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

