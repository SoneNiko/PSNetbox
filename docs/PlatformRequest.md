# PlatformRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Manufacturer** | [**NestedManufacturerRequest**](NestedManufacturerRequest.md) |  | [optional] 
**ConfigTemplate** | [**NestedConfigTemplateRequest**](NestedConfigTemplateRequest.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PlatformRequest = Initialize-PSOpenAPIToolsPlatformRequest  -Name null `
 -Slug null `
 -Manufacturer null `
 -ConfigTemplate null `
 -Description null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PlatformRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

