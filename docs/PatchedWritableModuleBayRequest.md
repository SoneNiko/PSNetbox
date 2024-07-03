# PatchedWritableModuleBayRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Device** | **Int32** |  | [optional] 
**Name** | **String** |  | [optional] 
**InstalledModule** | **Int32** |  | [optional] 
**Label** | **String** | Physical label | [optional] 
**Position** | **String** | Identifier to reference when renaming installed components | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableModuleBayRequest = Initialize-PSOpenAPIToolsPatchedWritableModuleBayRequest  -Device null `
 -Name null `
 -InstalledModule null `
 -Label null `
 -Position null `
 -Description null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableModuleBayRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

