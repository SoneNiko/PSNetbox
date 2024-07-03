# Interface
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Device** | [**NestedDevice**](NestedDevice.md) |  | 
**Vdcs** | **Int32[]** |  | [optional] 
**Module** | [**ComponentNestedModule**](ComponentNestedModule.md) |  | [optional] 
**Name** | **String** |  | 
**Label** | **String** | Physical label | [optional] 
**Type** | [**InterfaceType**](InterfaceType.md) |  | 
**Enabled** | **Boolean** |  | [optional] 
**Parent** | [**NestedInterface**](NestedInterface.md) |  | [optional] 
**Bridge** | [**NestedInterface**](NestedInterface.md) |  | [optional] 
**Lag** | [**NestedInterface**](NestedInterface.md) |  | [optional] 
**Mtu** | **Int32** |  | [optional] 
**MacAddress** | **String** |  | [optional] 
**Speed** | **Int32** |  | [optional] 
**Duplex** | [**InterfaceDuplex**](InterfaceDuplex.md) |  | [optional] 
**Wwn** | **String** |  | [optional] 
**MgmtOnly** | **Boolean** | This interface is used only for out-of-band management | [optional] 
**Description** | **String** |  | [optional] 
**Mode** | [**InterfaceMode**](InterfaceMode.md) |  | [optional] 
**RfRole** | [**InterfaceRfRole**](InterfaceRfRole.md) |  | [optional] 
**RfChannel** | [**InterfaceRfChannel**](InterfaceRfChannel.md) |  | [optional] 
**PoeMode** | [**InterfacePoeMode**](InterfacePoeMode.md) |  | [optional] 
**PoeType** | [**InterfacePoeType**](InterfacePoeType.md) |  | [optional] 
**RfChannelFrequency** | **Double** | Populated by selected channel (if set) | [optional] 
**RfChannelWidth** | **Double** | Populated by selected channel (if set) | [optional] 
**TxPower** | **Int32** |  | [optional] 
**UntaggedVlan** | [**NestedVLAN**](NestedVLAN.md) |  | [optional] 
**TaggedVlans** | **Int32[]** |  | [optional] 
**MarkConnected** | **Boolean** | Treat as if a cable is connected | [optional] 
**Cable** | [**NestedCable**](NestedCable.md) |  | [readonly] 
**CableEnd** | **String** |  | [readonly] 
**WirelessLink** | [**NestedWirelessLink**](NestedWirelessLink.md) |  | [readonly] 
**LinkPeers** | [**AnyType[]**](AnyType.md) |  | [readonly] 
**LinkPeersType** | **String** | Return the type of the peer link terminations, or None. | [readonly] 
**WirelessLans** | **Int32[]** |  | [optional] 
**Vrf** | [**NestedVRF**](NestedVRF.md) |  | [optional] 
**L2vpnTermination** | [**NestedL2VPNTermination**](NestedL2VPNTermination.md) |  | [readonly] 
**ConnectedEndpoints** | [**AnyType[]**](AnyType.md) |  | [readonly] 
**ConnectedEndpointsType** | **String** |  | [readonly] 
**ConnectedEndpointsReachable** | **Boolean** |  | [readonly] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**CountIpaddresses** | **Int32** |  | [readonly] 
**CountFhrpGroups** | **Int32** |  | [readonly] 
**Occupied** | **Boolean** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Interface = Initialize-PSOpenAPIToolsInterface  -Id null `
 -Url null `
 -Display null `
 -Device null `
 -Vdcs null `
 -Module null `
 -Name null `
 -Label null `
 -Type null `
 -Enabled null `
 -Parent null `
 -Bridge null `
 -Lag null `
 -Mtu null `
 -MacAddress null `
 -Speed null `
 -Duplex null `
 -Wwn null `
 -MgmtOnly null `
 -Description null `
 -Mode null `
 -RfRole null `
 -RfChannel null `
 -PoeMode null `
 -PoeType null `
 -RfChannelFrequency null `
 -RfChannelWidth null `
 -TxPower null `
 -UntaggedVlan null `
 -TaggedVlans null `
 -MarkConnected null `
 -Cable null `
 -CableEnd null `
 -WirelessLink null `
 -LinkPeers null `
 -LinkPeersType null `
 -WirelessLans null `
 -Vrf null `
 -L2vpnTermination null `
 -ConnectedEndpoints null `
 -ConnectedEndpointsType null `
 -ConnectedEndpointsReachable null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -CountIpaddresses null `
 -CountFhrpGroups null `
 -Occupied null
```

- Convert the resource to JSON
```powershell
$Interface | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

