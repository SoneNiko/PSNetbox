# PatchedWritableL2VPNTerminationRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**L2vpn** | **Int32** |  | [optional] 
**AssignedObjectType** | **String** |  | [optional] 
**AssignedObjectId** | **Int64** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableL2VPNTerminationRequest = Initialize-PSOpenAPIToolsPatchedWritableL2VPNTerminationRequest  -L2vpn null `
 -AssignedObjectType null `
 -AssignedObjectId null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableL2VPNTerminationRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

