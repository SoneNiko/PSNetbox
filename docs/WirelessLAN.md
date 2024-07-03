# WirelessLAN
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Ssid** | **String** |  | 
**Description** | **String** |  | [optional] 
**Group** | [**NestedWirelessLANGroup**](NestedWirelessLANGroup.md) |  | [optional] 
**Status** | [**WirelessLANStatus**](WirelessLANStatus.md) |  | [optional] 
**Vlan** | [**NestedVLAN**](NestedVLAN.md) |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**AuthType** | [**WirelessLANAuthType**](WirelessLANAuthType.md) |  | [optional] 
**AuthCipher** | [**WirelessLANAuthCipher**](WirelessLANAuthCipher.md) |  | [optional] 
**AuthPsk** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$WirelessLAN = Initialize-PSOpenAPIToolsWirelessLAN  -Id null `
 -Url null `
 -Display null `
 -Ssid null `
 -Description null `
 -Group null `
 -Status null `
 -Vlan null `
 -Tenant null `
 -AuthType null `
 -AuthCipher null `
 -AuthPsk null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$WirelessLAN | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

