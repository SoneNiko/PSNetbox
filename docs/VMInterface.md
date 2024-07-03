# VMInterface
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**VirtualMachine** | [**NestedVirtualMachine**](NestedVirtualMachine.md) |  | 
**Name** | **String** |  | 
**Enabled** | **Boolean** |  | [optional] 
**Parent** | [**NestedVMInterface**](NestedVMInterface.md) |  | [optional] 
**Bridge** | [**NestedVMInterface**](NestedVMInterface.md) |  | [optional] 
**Mtu** | **Int32** |  | [optional] 
**MacAddress** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**Mode** | [**InterfaceMode**](InterfaceMode.md) |  | [optional] 
**UntaggedVlan** | [**NestedVLAN**](NestedVLAN.md) |  | [optional] 
**TaggedVlans** | **Int32[]** |  | [optional] 
**Vrf** | [**NestedVRF**](NestedVRF.md) |  | [optional] 
**L2vpnTermination** | [**NestedL2VPNTermination**](NestedL2VPNTermination.md) |  | [readonly] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**CountIpaddresses** | **Int32** |  | [readonly] 
**CountFhrpGroups** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$VMInterface = Initialize-PSOpenAPIToolsVMInterface  -Id null `
 -Url null `
 -Display null `
 -VirtualMachine null `
 -Name null `
 -Enabled null `
 -Parent null `
 -Bridge null `
 -Mtu null `
 -MacAddress null `
 -Description null `
 -Mode null `
 -UntaggedVlan null `
 -TaggedVlans null `
 -Vrf null `
 -L2vpnTermination null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -CountIpaddresses null `
 -CountFhrpGroups null
```

- Convert the resource to JSON
```powershell
$VMInterface | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

