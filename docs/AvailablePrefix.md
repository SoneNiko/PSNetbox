# AvailablePrefix
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Family** | **Int32** |  | [readonly] 
**Prefix** | **String** |  | [readonly] 
**Vrf** | [**NestedVRF**](NestedVRF.md) |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$AvailablePrefix = Initialize-PSOpenAPIToolsAvailablePrefix  -Family null `
 -Prefix null `
 -Vrf null
```

- Convert the resource to JSON
```powershell
$AvailablePrefix | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

