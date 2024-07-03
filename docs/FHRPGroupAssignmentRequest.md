# FHRPGroupAssignmentRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Group** | [**NestedFHRPGroupRequest**](NestedFHRPGroupRequest.md) |  | 
**InterfaceType** | **String** |  | 
**InterfaceId** | **Int64** |  | 
**Priority** | **Int32** |  | 

## Examples

- Prepare the resource
```powershell
$FHRPGroupAssignmentRequest = Initialize-PSOpenAPIToolsFHRPGroupAssignmentRequest  -Group null `
 -InterfaceType null `
 -InterfaceId null `
 -Priority null
```

- Convert the resource to JSON
```powershell
$FHRPGroupAssignmentRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

