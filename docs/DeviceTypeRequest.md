# DeviceTypeRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Manufacturer** | [**NestedManufacturerRequest**](NestedManufacturerRequest.md) |  | 
**DefaultPlatform** | [**NestedPlatformRequest**](NestedPlatformRequest.md) |  | [optional] 
**Model** | **String** |  | 
**Slug** | **String** |  | 
**PartNumber** | **String** | Discrete part number (optional) | [optional] 
**UHeight** | **Double** |  | [optional] [default to 1.0]
**ExcludeFromUtilization** | **Boolean** | Devices of this type are excluded when calculating rack utilization. | [optional] 
**IsFullDepth** | **Boolean** | Device consumes both front and rear rack faces. | [optional] 
**SubdeviceRole** | **String** | * &#x60;parent&#x60; - Parent * &#x60;child&#x60; - Child | [optional] 
**Airflow** | **String** | * &#x60;front-to-rear&#x60; - Front to rear * &#x60;rear-to-front&#x60; - Rear to front * &#x60;left-to-right&#x60; - Left to right * &#x60;right-to-left&#x60; - Right to left * &#x60;side-to-rear&#x60; - Side to rear * &#x60;passive&#x60; - Passive * &#x60;mixed&#x60; - Mixed | [optional] 
**Weight** | **Double** |  | [optional] 
**WeightUnit** | **String** | * &#x60;kg&#x60; - Kilograms * &#x60;g&#x60; - Grams * &#x60;lb&#x60; - Pounds * &#x60;oz&#x60; - Ounces | [optional] 
**FrontImage** | **System.IO.FileInfo** |  | [optional] 
**RearImage** | **System.IO.FileInfo** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$DeviceTypeRequest = Initialize-PSOpenAPIToolsDeviceTypeRequest  -Manufacturer null `
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
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$DeviceTypeRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

