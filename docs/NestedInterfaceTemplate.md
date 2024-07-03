# NestedInterfaceTemplate
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** | {module} is accepted as a substitution for the module bay position when attached to a module type. | 

## Examples

- Prepare the resource
```powershell
$NestedInterfaceTemplate = Initialize-PSOpenAPIToolsNestedInterfaceTemplate  -Id null `
 -Url null `
 -Display null `
 -Name null
```

- Convert the resource to JSON
```powershell
$NestedInterfaceTemplate | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

