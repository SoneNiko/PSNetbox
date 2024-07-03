# PowerPortTemplate
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
**Type** | [**PowerPortType**](PowerPortType.md) |  | [optional] 
**MaximumDraw** | **Int32** | Maximum power draw (watts) | [optional] 
**AllocatedDraw** | **Int32** | Allocated power draw (watts) | [optional] 
**Description** | **String** |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$PowerPortTemplate = Initialize-PSOpenAPIToolsPowerPortTemplate  -Id null `
 -Url null `
 -Display null `
 -DeviceType null `
 -ModuleType null `
 -Name null `
 -Label null `
 -Type null `
 -MaximumDraw null `
 -AllocatedDraw null `
 -Description null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$PowerPortTemplate | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

