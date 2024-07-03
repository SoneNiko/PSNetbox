# CircuitCircuitTermination
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Site** | [**NestedSite**](NestedSite.md) |  | 
**ProviderNetwork** | [**NestedProviderNetwork**](NestedProviderNetwork.md) |  | 
**PortSpeed** | **Int32** | Physical circuit speed | [optional] 
**UpstreamSpeed** | **Int32** | Upstream speed, if different from port speed | [optional] 
**XconnectId** | **String** | ID of the local cross-connect | [optional] 
**Description** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$CircuitCircuitTermination = Initialize-PSOpenAPIToolsCircuitCircuitTermination  -Id null `
 -Url null `
 -Display null `
 -Site null `
 -ProviderNetwork null `
 -PortSpeed null `
 -UpstreamSpeed null `
 -XconnectId null `
 -Description null
```

- Convert the resource to JSON
```powershell
$CircuitCircuitTermination | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

