# NestedDeviceType
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Manufacturer** | [**NestedManufacturer**](NestedManufacturer.md) |  | [readonly] 
**Model** | **String** |  | 
**Slug** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$NestedDeviceType = Initialize-PSOpenAPIToolsNestedDeviceType  -Id null `
 -Url null `
 -Display null `
 -Manufacturer null `
 -Model null `
 -Slug null
```

- Convert the resource to JSON
```powershell
$NestedDeviceType | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

