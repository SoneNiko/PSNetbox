# Job
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**ObjectType** | **String** |  | [readonly] 
**ObjectId** | **Int64** |  | [optional] 
**Name** | **String** |  | 
**Status** | [**JobStatus**](JobStatus.md) |  | 
**Created** | **System.DateTime** |  | [readonly] 
**Scheduled** | **System.DateTime** |  | [optional] 
**Interval** | **Int32** | Recurrence interval (in minutes) | [optional] 
**Started** | **System.DateTime** |  | [optional] 
**Completed** | **System.DateTime** |  | [optional] 
**User** | [**NestedUser**](NestedUser.md) |  | [readonly] 
**VarData** | [**AnyType**](.md) |  | [optional] 
**VarError** | **String** |  | [readonly] 
**JobId** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$Job = Initialize-PSOpenAPIToolsJob  -Id null `
 -Url null `
 -Display null `
 -ObjectType null `
 -ObjectId null `
 -Name null `
 -Status null `
 -Created null `
 -Scheduled null `
 -Interval null `
 -Started null `
 -Completed null `
 -User null `
 -VarData null `
 -VarError null `
 -JobId null
```

- Convert the resource to JSON
```powershell
$Job | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

