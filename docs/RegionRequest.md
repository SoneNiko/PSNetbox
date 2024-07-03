# RegionRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Parent** | [**NestedRegionRequest**](NestedRegionRequest.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$RegionRequest = Initialize-PSOpenAPIToolsRegionRequest  -Name null `
 -Slug null `
 -Parent null `
 -Description null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$RegionRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

