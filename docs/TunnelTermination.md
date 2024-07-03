# TunnelTermination
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Tunnel** | [**NestedTunnel**](NestedTunnel.md) |  | 
**Role** | [**TunnelTerminationRole**](TunnelTerminationRole.md) |  | 
**TerminationType** | **String** |  | 
**TerminationId** | **Int64** |  | [optional] 
**Termination** | [**AnyType**](.md) |  | [readonly] 
**OutsideIp** | [**NestedIPAddress**](NestedIPAddress.md) |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$TunnelTermination = Initialize-PSOpenAPIToolsTunnelTermination  -Id null `
 -Url null `
 -Display null `
 -Tunnel null `
 -Role null `
 -TerminationType null `
 -TerminationId null `
 -Termination null `
 -OutsideIp null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$TunnelTermination | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

