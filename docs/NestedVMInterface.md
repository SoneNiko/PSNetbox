# NestedVMInterface
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**VirtualMachine** | [**NestedVirtualMachine**](NestedVirtualMachine.md) |  | [readonly] 
**Name** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$NestedVMInterface = Initialize-PSOpenAPIToolsNestedVMInterface  -Id null `
 -Url null `
 -Display null `
 -VirtualMachine null `
 -Name null
```

- Convert the resource to JSON
```powershell
$NestedVMInterface | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

