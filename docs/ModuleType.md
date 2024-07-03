# ModuleType
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Manufacturer** | [**NestedManufacturer**](NestedManufacturer.md) |  | 
**Model** | **String** |  | 
**PartNumber** | **String** | Discrete part number (optional) | [optional] 
**Weight** | **Double** |  | [optional] 
**WeightUnit** | [**DeviceTypeWeightUnit**](DeviceTypeWeightUnit.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$ModuleType = Initialize-PSOpenAPIToolsModuleType  -Id null `
 -Url null `
 -Display null `
 -Manufacturer null `
 -Model null `
 -PartNumber null `
 -Weight null `
 -WeightUnit null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$ModuleType | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

