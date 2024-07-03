# PatchedWritableCircuitTerminationRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Circuit** | **Int32** |  | [optional] 
**TermSide** | **String** | * &#x60;A&#x60; - A * &#x60;Z&#x60; - Z | [optional] 
**Site** | **Int32** |  | [optional] 
**ProviderNetwork** | **Int32** |  | [optional] 
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
$PatchedWritableCircuitTerminationRequest = Initialize-PSOpenAPIToolsPatchedWritableCircuitTerminationRequest  -Circuit null `
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
$PatchedWritableCircuitTerminationRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

