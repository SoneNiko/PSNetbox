# PatchedWritableDeviceBayRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Device** | **Int32** |  | [optional] 
**Name** | **String** |  | [optional] 
**Label** | **String** | Physical label | [optional] 
**Description** | **String** |  | [optional] 
**InstalledDevice** | **Int32** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableDeviceBayRequest = Initialize-PSOpenAPIToolsPatchedWritableDeviceBayRequest  -Device null `
 -Name null `
 -Label null `
 -Description null `
 -InstalledDevice null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableDeviceBayRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

