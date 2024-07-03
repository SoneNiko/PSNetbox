# ImageAttachment
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**ContentType** | **String** |  | 
**ObjectId** | **Int64** |  | 
**Parent** | [**AnyType**](.md) |  | [readonly] 
**Name** | **String** |  | [optional] 
**Image** | **String** |  | 
**ImageHeight** | **Int32** |  | 
**ImageWidth** | **Int32** |  | 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$ImageAttachment = Initialize-PSOpenAPIToolsImageAttachment  -Id null `
 -Url null `
 -Display null `
 -ContentType null `
 -ObjectId null `
 -Parent null `
 -Name null `
 -Image null `
 -ImageHeight null `
 -ImageWidth null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$ImageAttachment | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

