# L2VPNTerminationRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**L2vpn** | [**NestedL2VPNRequest**](NestedL2VPNRequest.md) |  | 
**AssignedObjectType** | **String** |  | 
**AssignedObjectId** | **Int64** |  | 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$L2VPNTerminationRequest = Initialize-PSOpenAPIToolsL2VPNTerminationRequest  -L2vpn null `
 -AssignedObjectType null `
 -AssignedObjectId null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$L2VPNTerminationRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

