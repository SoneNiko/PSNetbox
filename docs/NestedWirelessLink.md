# NestedWirelessLink
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Ssid** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$NestedWirelessLink = Initialize-PSOpenAPIToolsNestedWirelessLink  -Id null `
 -Url null `
 -Display null `
 -Ssid null
```

- Convert the resource to JSON
```powershell
$NestedWirelessLink | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

