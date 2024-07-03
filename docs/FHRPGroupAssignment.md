# FHRPGroupAssignment
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Group** | [**NestedFHRPGroup**](NestedFHRPGroup.md) |  | 
**InterfaceType** | **String** |  | 
**InterfaceId** | **Int64** |  | 
**Interface** | [**AnyType**](.md) |  | [readonly] 
**Priority** | **Int32** |  | 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$FHRPGroupAssignment = Initialize-PSOpenAPIToolsFHRPGroupAssignment  -Id null `
 -Url null `
 -Display null `
 -Group null `
 -InterfaceType null `
 -InterfaceId null `
 -Interface null `
 -Priority null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$FHRPGroupAssignment | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

