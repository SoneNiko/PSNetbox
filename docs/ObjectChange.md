# ObjectChange
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Time** | **System.DateTime** |  | [readonly] 
**User** | [**NestedUser**](NestedUser.md) |  | [readonly] 
**UserName** | **String** |  | [readonly] 
**RequestId** | **String** |  | [readonly] 
**Action** | [**ObjectChangeAction**](ObjectChangeAction.md) |  | 
**ChangedObjectType** | **String** |  | [readonly] 
**ChangedObjectId** | **Int64** |  | 
**ChangedObject** | [**AnyType**](.md) |  | [readonly] 
**PrechangeData** | [**AnyType**](.md) |  | [readonly] 
**PostchangeData** | [**AnyType**](.md) |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$ObjectChange = Initialize-PSOpenAPIToolsObjectChange  -Id null `
 -Url null `
 -Display null `
 -Time null `
 -User null `
 -UserName null `
 -RequestId null `
 -Action null `
 -ChangedObjectType null `
 -ChangedObjectId null `
 -ChangedObject null `
 -PrechangeData null `
 -PostchangeData null
```

- Convert the resource to JSON
```powershell
$ObjectChange | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

