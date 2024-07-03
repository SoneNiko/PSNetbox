# NestedVLANRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Vid** | **Int32** | Numeric VLAN ID (1-4094) | 
**Name** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$NestedVLANRequest = Initialize-PSOpenAPIToolsNestedVLANRequest  -Vid null `
 -Name null
```

- Convert the resource to JSON
```powershell
$NestedVLANRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

