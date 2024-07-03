# NestedVirtualMachine
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$NestedVirtualMachine = Initialize-PSOpenAPIToolsNestedVirtualMachine  -Id null `
 -Url null `
 -Display null `
 -Name null
```

- Convert the resource to JSON
```powershell
$NestedVirtualMachine | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

