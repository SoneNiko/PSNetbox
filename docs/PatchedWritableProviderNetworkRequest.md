# PatchedWritableProviderNetworkRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Provider** | **Int32** |  | [optional] 
**Name** | **String** |  | [optional] 
**ServiceId** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableProviderNetworkRequest = Initialize-PSOpenAPIToolsPatchedWritableProviderNetworkRequest  -Provider null `
 -Name null `
 -ServiceId null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableProviderNetworkRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

