# PatchedWritableDeviceBayTemplateRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceType** | **Int32** |  | [optional] 
**Name** | **String** | {module} is accepted as a substitution for the module bay position when attached to a module type. | [optional] 
**Label** | **String** | Physical label | [optional] 
**Description** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableDeviceBayTemplateRequest = Initialize-PSOpenAPIToolsPatchedWritableDeviceBayTemplateRequest  -DeviceType null `
 -Name null `
 -Label null `
 -Description null
```

- Convert the resource to JSON
```powershell
$PatchedWritableDeviceBayTemplateRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

