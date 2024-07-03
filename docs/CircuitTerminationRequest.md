# CircuitTerminationRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Circuit** | [**NestedCircuitRequest**](NestedCircuitRequest.md) |  | 
**TermSide** | **String** | * &#x60;A&#x60; - A * &#x60;Z&#x60; - Z | 
**Site** | [**NestedSiteRequest**](NestedSiteRequest.md) |  | [optional] 
**ProviderNetwork** | [**NestedProviderNetworkRequest**](NestedProviderNetworkRequest.md) |  | [optional] 
**PortSpeed** | **Int32** | Physical circuit speed | [optional] 
**UpstreamSpeed** | **Int32** | Upstream speed, if different from port speed | [optional] 
**XconnectId** | **String** | ID of the local cross-connect | [optional] 
**PpInfo** | **String** | Patch panel ID and port number(s) | [optional] 
**Description** | **String** |  | [optional] 
**MarkConnected** | **Boolean** | Treat as if a cable is connected | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$CircuitTerminationRequest = Initialize-PSOpenAPIToolsCircuitTerminationRequest  -Circuit null `
 -TermSide null `
 -Site null `
 -ProviderNetwork null `
 -PortSpeed null `
 -UpstreamSpeed null `
 -XconnectId null `
 -PpInfo null `
 -Description null `
 -MarkConnected null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$CircuitTerminationRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

