# PatchedWritableIPSecProfileRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**Mode** | **String** | * &#x60;esp&#x60; - ESP * &#x60;ah&#x60; - AH | [optional] 
**IkePolicy** | **Int32** |  | [optional] 
**IpsecPolicy** | **Int32** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableIPSecProfileRequest = Initialize-PSOpenAPIToolsPatchedWritableIPSecProfileRequest  -Name null `
 -Description null `
 -Mode null `
 -IkePolicy null `
 -IpsecPolicy null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableIPSecProfileRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

