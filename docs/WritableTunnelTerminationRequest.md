# WritableTunnelTerminationRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tunnel** | **Int32** |  | 
**Role** | **String** | * &#x60;peer&#x60; - Peer * &#x60;hub&#x60; - Hub * &#x60;spoke&#x60; - Spoke | [optional] 
**TerminationType** | **String** |  | 
**TerminationId** | **Int64** |  | [optional] 
**OutsideIp** | **Int32** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableTunnelTerminationRequest = Initialize-PSOpenAPIToolsWritableTunnelTerminationRequest  -Tunnel null `
 -Role null `
 -TerminationType null `
 -TerminationId null `
 -OutsideIp null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$WritableTunnelTerminationRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

