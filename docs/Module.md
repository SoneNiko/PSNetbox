# Module
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Device** | [**NestedDevice**](NestedDevice.md) |  | 
**ModuleBay** | [**NestedModuleBay**](NestedModuleBay.md) |  | 
**ModuleType** | [**NestedModuleType**](NestedModuleType.md) |  | 
**Status** | [**ModuleStatus**](ModuleStatus.md) |  | [optional] 
**Serial** | **String** |  | [optional] 
**AssetTag** | **String** | A unique tag used to identify this device | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Module = Initialize-PSOpenAPIToolsModule  -Id null `
 -Url null `
 -Display null `
 -Device null `
 -ModuleBay null `
 -ModuleType null `
 -Status null `
 -Serial null `
 -AssetTag null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$Module | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

