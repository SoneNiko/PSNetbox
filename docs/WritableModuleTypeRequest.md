# WritableModuleTypeRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Manufacturer** | **Int32** |  | 
**Model** | **String** |  | 
**PartNumber** | **String** | Discrete part number (optional) | [optional] 
**Weight** | **Double** |  | [optional] 
**WeightUnit** | **String** | * &#x60;kg&#x60; - Kilograms * &#x60;g&#x60; - Grams * &#x60;lb&#x60; - Pounds * &#x60;oz&#x60; - Ounces | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableModuleTypeRequest = Initialize-PSOpenAPIToolsWritableModuleTypeRequest  -Manufacturer null `
 -Model null `
 -PartNumber null `
 -Weight null `
 -WeightUnit null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$WritableModuleTypeRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

