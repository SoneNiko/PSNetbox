# NestedL2VPNTermination
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**L2vpn** | [**NestedL2VPN**](NestedL2VPN.md) |  | 

## Examples

- Prepare the resource
```powershell
$NestedL2VPNTermination = Initialize-PSOpenAPIToolsNestedL2VPNTermination  -Id null `
 -Url null `
 -Display null `
 -L2vpn null
```

- Convert the resource to JSON
```powershell
$NestedL2VPNTermination | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

