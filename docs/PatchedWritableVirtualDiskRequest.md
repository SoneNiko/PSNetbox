# PatchedWritableVirtualDiskRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**VirtualMachine** | **Int32** |  | [optional] 
**Name** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**Size** | **Int32** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableVirtualDiskRequest = Initialize-PSOpenAPIToolsPatchedWritableVirtualDiskRequest  -VirtualMachine null `
 -Name null `
 -Description null `
 -Size null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableVirtualDiskRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

