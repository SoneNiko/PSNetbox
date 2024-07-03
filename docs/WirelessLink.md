# WirelessLink
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**InterfaceA** | [**NestedInterface**](NestedInterface.md) |  | 
**InterfaceB** | [**NestedInterface**](NestedInterface.md) |  | 
**Ssid** | **String** |  | [optional] 
**Status** | [**CableStatus**](CableStatus.md) |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**AuthType** | [**WirelessLANAuthType**](WirelessLANAuthType.md) |  | [optional] 
**AuthCipher** | [**WirelessLANAuthCipher**](WirelessLANAuthCipher.md) |  | [optional] 
**AuthPsk** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$WirelessLink = Initialize-PSOpenAPIToolsWirelessLink  -Id null `
 -Url null `
 -Display null `
 -InterfaceA null `
 -InterfaceB null `
 -Ssid null `
 -Status null `
 -Tenant null `
 -AuthType null `
 -AuthCipher null `
 -AuthPsk null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$WirelessLink | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

