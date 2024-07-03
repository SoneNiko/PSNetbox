# WritablePlatformRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Manufacturer** | **Int32** | Optionally limit this platform to devices of a certain manufacturer | [optional] 
**ConfigTemplate** | **Int32** |  | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritablePlatformRequest = Initialize-PSOpenAPIToolsWritablePlatformRequest  -Name null `
 -Slug null `
 -Manufacturer null `
 -ConfigTemplate null `
 -Description null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$WritablePlatformRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

