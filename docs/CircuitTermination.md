# CircuitTermination
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Circuit** | [**NestedCircuit**](NestedCircuit.md) |  | 
**TermSide** | **String** | * &#x60;A&#x60; - A * &#x60;Z&#x60; - Z | 
**Site** | [**NestedSite**](NestedSite.md) |  | [optional] 
**ProviderNetwork** | [**NestedProviderNetwork**](NestedProviderNetwork.md) |  | [optional] 
**PortSpeed** | **Int32** | Physical circuit speed | [optional] 
**UpstreamSpeed** | **Int32** | Upstream speed, if different from port speed | [optional] 
**XconnectId** | **String** | ID of the local cross-connect | [optional] 
**PpInfo** | **String** | Patch panel ID and port number(s) | [optional] 
**Description** | **String** |  | [optional] 
**MarkConnected** | **Boolean** | Treat as if a cable is connected | [optional] 
**Cable** | [**NestedCable**](NestedCable.md) |  | [readonly] 
**CableEnd** | **String** |  | [readonly] 
**LinkPeers** | [**AnyType[]**](AnyType.md) |  | [readonly] 
**LinkPeersType** | **String** | Return the type of the peer link terminations, or None. | [readonly] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**Occupied** | **Boolean** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$CircuitTermination = Initialize-PSOpenAPIToolsCircuitTermination  -Id null `
 -Url null `
 -Display null `
 -Circuit null `
 -TermSide null `
 -Site null `
 -ProviderNetwork null `
 -PortSpeed null `
 -UpstreamSpeed null `
 -XconnectId null `
 -PpInfo null `
 -Description null `
 -MarkConnected null `
 -Cable null `
 -CableEnd null `
 -LinkPeers null `
 -LinkPeersType null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -Occupied null
```

- Convert the resource to JSON
```powershell
$CircuitTermination | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

