# VirtualDisk
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**VirtualMachine** | [**NestedVirtualMachine**](NestedVirtualMachine.md) |  | 
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**Size** | **Int32** |  | 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$VirtualDisk = Initialize-PSOpenAPIToolsVirtualDisk  -Id null `
 -Url null `
 -Display null `
 -VirtualMachine null `
 -Name null `
 -Description null `
 -Size null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$VirtualDisk | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

