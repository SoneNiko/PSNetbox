# DeviceType
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Manufacturer** | [**NestedManufacturer**](NestedManufacturer.md) |  | 
**DefaultPlatform** | [**NestedPlatform**](NestedPlatform.md) |  | [optional] 
**Model** | **String** |  | 
**Slug** | **String** |  | 
**PartNumber** | **String** | Discrete part number (optional) | [optional] 
**UHeight** | **Double** |  | [optional] [default to 1.0]
**ExcludeFromUtilization** | **Boolean** | Devices of this type are excluded when calculating rack utilization. | [optional] 
**IsFullDepth** | **Boolean** | Device consumes both front and rear rack faces. | [optional] 
**SubdeviceRole** | [**DeviceTypeSubdeviceRole**](DeviceTypeSubdeviceRole.md) |  | [optional] 
**Airflow** | [**DeviceTypeAirflow**](DeviceTypeAirflow.md) |  | [optional] 
**Weight** | **Double** |  | [optional] 
**WeightUnit** | [**DeviceTypeWeightUnit**](DeviceTypeWeightUnit.md) |  | [optional] 
**FrontImage** | **String** |  | [optional] 
**RearImage** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**DeviceCount** | **Int32** |  | [readonly] 
**ConsolePortTemplateCount** | **Int32** |  | [readonly] 
**ConsoleServerPortTemplateCount** | **Int32** |  | [readonly] 
**PowerPortTemplateCount** | **Int32** |  | [readonly] 
**PowerOutletTemplateCount** | **Int32** |  | [readonly] 
**InterfaceTemplateCount** | **Int32** |  | [readonly] 
**FrontPortTemplateCount** | **Int32** |  | [readonly] 
**RearPortTemplateCount** | **Int32** |  | [readonly] 
**DeviceBayTemplateCount** | **Int32** |  | [readonly] 
**ModuleBayTemplateCount** | **Int32** |  | [readonly] 
**InventoryItemTemplateCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$DeviceType = Initialize-PSOpenAPIToolsDeviceType  -Id null `
 -Url null `
 -Display null `
 -Manufacturer null `
 -DefaultPlatform null `
 -Model null `
 -Slug null `
 -PartNumber null `
 -UHeight null `
 -ExcludeFromUtilization null `
 -IsFullDepth null `
 -SubdeviceRole null `
 -Airflow null `
 -Weight null `
 -WeightUnit null `
 -FrontImage null `
 -RearImage null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -DeviceCount null `
 -ConsolePortTemplateCount null `
 -ConsoleServerPortTemplateCount null `
 -PowerPortTemplateCount null `
 -PowerOutletTemplateCount null `
 -InterfaceTemplateCount null `
 -FrontPortTemplateCount null `
 -RearPortTemplateCount null `
 -DeviceBayTemplateCount null `
 -ModuleBayTemplateCount null `
 -InventoryItemTemplateCount null
```

- Convert the resource to JSON
```powershell
$DeviceType | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

