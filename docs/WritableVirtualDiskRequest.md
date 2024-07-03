# WritableVirtualDiskRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**VirtualMachine** | **Int32** |  | 
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**Size** | **Int32** |  | 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableVirtualDiskRequest = Initialize-PSOpenAPIToolsWritableVirtualDiskRequest  -VirtualMachine null `
 -Name null `
 -Description null `
 -Size null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$WritableVirtualDiskRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

