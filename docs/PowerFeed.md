# PowerFeed
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**PowerPanel** | [**NestedPowerPanel**](NestedPowerPanel.md) |  | 
**Rack** | [**NestedRack**](NestedRack.md) |  | [optional] 
**Name** | **String** |  | 
**Status** | [**PowerFeedStatus**](PowerFeedStatus.md) |  | [optional] 
**Type** | [**PowerFeedType**](PowerFeedType.md) |  | [optional] 
**Supply** | [**PowerFeedSupply**](PowerFeedSupply.md) |  | [optional] 
**Phase** | [**PowerFeedPhase**](PowerFeedPhase.md) |  | [optional] 
**Voltage** | **Int32** |  | [optional] 
**Amperage** | **Int32** |  | [optional] 
**MaxUtilization** | **Int32** | Maximum permissible draw (percentage) | [optional] 
**MarkConnected** | **Boolean** | Treat as if a cable is connected | [optional] 
**Cable** | [**NestedCable**](NestedCable.md) |  | [readonly] 
**CableEnd** | **String** |  | [readonly] 
**LinkPeers** | [**AnyType[]**](AnyType.md) |  | [readonly] 
**LinkPeersType** | **String** | Return the type of the peer link terminations, or None. | [readonly] 
**ConnectedEndpoints** | [**AnyType[]**](AnyType.md) |  | [readonly] 
**ConnectedEndpointsType** | **String** |  | [readonly] 
**ConnectedEndpointsReachable** | **Boolean** |  | [readonly] 
**Description** | **String** |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**Occupied** | **Boolean** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$PowerFeed = Initialize-PSOpenAPIToolsPowerFeed  -Id null `
 -Url null `
 -Display null `
 -PowerPanel null `
 -Rack null `
 -Name null `
 -Status null `
 -Type null `
 -Supply null `
 -Phase null `
 -Voltage null `
 -Amperage null `
 -MaxUtilization null `
 -MarkConnected null `
 -Cable null `
 -CableEnd null `
 -LinkPeers null `
 -LinkPeersType null `
 -ConnectedEndpoints null `
 -ConnectedEndpointsType null `
 -ConnectedEndpointsReachable null `
 -Description null `
 -Tenant null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -Occupied null
```

- Convert the resource to JSON
```powershell
$PowerFeed | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

