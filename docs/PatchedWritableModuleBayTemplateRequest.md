# PatchedWritableModuleBayTemplateRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceType** | **Int32** |  | [optional] 
**Name** | **String** | {module} is accepted as a substitution for the module bay position when attached to a module type. | [optional] 
**Label** | **String** | Physical label | [optional] 
**Position** | **String** | Identifier to reference when renaming installed components | [optional] 
**Description** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableModuleBayTemplateRequest = Initialize-PSOpenAPIToolsPatchedWritableModuleBayTemplateRequest  -DeviceType null `
 -Name null `
 -Label null `
 -Position null `
 -Description null
```

- Convert the resource to JSON
```powershell
$PatchedWritableModuleBayTemplateRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

