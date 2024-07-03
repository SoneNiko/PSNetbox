# CircuitCircuitTerminationRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Site** | [**NestedSiteRequest**](NestedSiteRequest.md) |  | 
**ProviderNetwork** | [**NestedProviderNetworkRequest**](NestedProviderNetworkRequest.md) |  | 
**PortSpeed** | **Int32** | Physical circuit speed | [optional] 
**UpstreamSpeed** | **Int32** | Upstream speed, if different from port speed | [optional] 
**XconnectId** | **String** | ID of the local cross-connect | [optional] 
**Description** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$CircuitCircuitTerminationRequest = Initialize-PSOpenAPIToolsCircuitCircuitTerminationRequest  -Site null `
 -ProviderNetwork null `
 -PortSpeed null `
 -UpstreamSpeed null `
 -XconnectId null `
 -Description null
```

- Convert the resource to JSON
```powershell
$CircuitCircuitTerminationRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

