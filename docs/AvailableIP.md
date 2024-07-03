# AvailableIP
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Family** | **Int32** |  | [readonly] 
**Address** | **String** |  | [readonly] 
**Vrf** | [**NestedVRF**](NestedVRF.md) |  | [readonly] 
**Description** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$AvailableIP = Initialize-PSOpenAPIToolsAvailableIP  -Family null `
 -Address null `
 -Vrf null `
 -Description null
```

- Convert the resource to JSON
```powershell
$AvailableIP | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

