# RearPortTemplate
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
**Type** | [**FrontPortType**](FrontPortType.md) |  | 
**Color** | **String** |  | [optional] 
**Positions** | **Int32** |  | [optional] 
**Description** | **String** |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$RearPortTemplate = Initialize-PSOpenAPIToolsRearPortTemplate  -Id null `
 -Url null `
 -Display null `
 -DeviceType null `
 -ModuleType null `
 -Name null `
 -Label null `
 -Type null `
 -Color null `
 -Positions null `
 -Description null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$RearPortTemplate | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

