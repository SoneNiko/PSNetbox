# InterfaceTemplate
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**DeviceType** | [**NestedDeviceType**](NestedDeviceType.md) |  | [optional] 
**ModuleType** | [**NestedModuleType**](NestedModuleType.md) |  | [optional] 
**Name** | **String** | {module} is accepted as a substitution for the module bay position when attached to a module type. | 
**Label** | **String** | Physical label | [optional] 
**Type** | [**InterfaceType**](InterfaceType.md) |  | 
**Enabled** | **Boolean** |  | [optional] 
**MgmtOnly** | **Boolean** |  | [optional] 
**Description** | **String** |  | [optional] 
**Bridge** | [**NestedInterfaceTemplate**](NestedInterfaceTemplate.md) |  | [optional] 
**PoeMode** | [**InterfaceTemplatePoeMode**](InterfaceTemplatePoeMode.md) |  | [optional] 
**PoeType** | [**InterfaceTemplatePoeType**](InterfaceTemplatePoeType.md) |  | [optional] 
**RfRole** | [**InterfaceTemplateRfRole**](InterfaceTemplateRfRole.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$InterfaceTemplate = Initialize-PSOpenAPIToolsInterfaceTemplate  -Id null `
 -Url null `
 -Display null `
 -DeviceType null `
 -ModuleType null `
 -Name null `
 -Label null `
 -Type null `
 -Enabled null `
 -MgmtOnly null `
 -Description null `
 -Bridge null `
 -PoeMode null `
 -PoeType null `
 -RfRole null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$InterfaceTemplate | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

