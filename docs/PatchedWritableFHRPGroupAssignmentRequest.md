# PatchedWritableFHRPGroupAssignmentRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Group** | **Int32** |  | [optional] 
**InterfaceType** | **String** |  | [optional] 
**InterfaceId** | **Int64** |  | [optional] 
**Priority** | **Int32** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableFHRPGroupAssignmentRequest = Initialize-PSOpenAPIToolsPatchedWritableFHRPGroupAssignmentRequest  -Group null `
 -InterfaceType null `
 -InterfaceId null `
 -Priority null
```

- Convert the resource to JSON
```powershell
$PatchedWritableFHRPGroupAssignmentRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

