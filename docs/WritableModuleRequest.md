# WritableModuleRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Device** | **Int32** |  | 
**ModuleBay** | **Int32** |  | 
**ModuleType** | **Int32** |  | 
**Status** | **String** | * &#x60;offline&#x60; - Offline * &#x60;active&#x60; - Active * &#x60;planned&#x60; - Planned * &#x60;staged&#x60; - Staged * &#x60;failed&#x60; - Failed * &#x60;decommissioning&#x60; - Decommissioning | [optional] 
**Serial** | **String** |  | [optional] 
**AssetTag** | **String** | A unique tag used to identify this device | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableModuleRequest = Initialize-PSOpenAPIToolsWritableModuleRequest  -Device null `
 -ModuleBay null `
 -ModuleType null `
 -Status null `
 -Serial null `
 -AssetTag null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$WritableModuleRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

