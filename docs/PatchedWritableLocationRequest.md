# PatchedWritableLocationRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | [optional] 
**Slug** | **String** |  | [optional] 
**Site** | **Int32** |  | [optional] 
**Parent** | **Int32** |  | [optional] 
**Status** | **String** | * &#x60;planned&#x60; - Planned * &#x60;staging&#x60; - Staging * &#x60;active&#x60; - Active * &#x60;decommissioning&#x60; - Decommissioning * &#x60;retired&#x60; - Retired | [optional] 
**Tenant** | **Int32** |  | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableLocationRequest = Initialize-PSOpenAPIToolsPatchedWritableLocationRequest  -Name null `
 -Slug null `
 -Site null `
 -Parent null `
 -Status null `
 -Tenant null `
 -Description null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableLocationRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

