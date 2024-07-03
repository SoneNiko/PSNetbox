# NestedPowerPort
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Device** | [**NestedDevice**](NestedDevice.md) |  | [readonly] 
**Name** | **String** |  | 
**Cable** | **Int32** |  | [optional] 
**Occupied** | **Boolean** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$NestedPowerPort = Initialize-PSOpenAPIToolsNestedPowerPort  -Id null `
 -Url null `
 -Display null `
 -Device null `
 -Name null `
 -Cable null `
 -Occupied null
```

- Convert the resource to JSON
```powershell
$NestedPowerPort | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

