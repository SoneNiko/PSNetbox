# PatchedWritablePowerPanelRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Site** | **Int32** |  | [optional] 
**Location** | **Int32** |  | [optional] 
**Name** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritablePowerPanelRequest = Initialize-PSOpenAPIToolsPatchedWritablePowerPanelRequest  -Site null `
 -Location null `
 -Name null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritablePowerPanelRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

