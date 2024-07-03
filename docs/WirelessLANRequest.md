# WirelessLANRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ssid** | **String** |  | 
**Description** | **String** |  | [optional] 
**Group** | [**NestedWirelessLANGroupRequest**](NestedWirelessLANGroupRequest.md) |  | [optional] 
**Status** | **String** | * &#x60;active&#x60; - Active * &#x60;reserved&#x60; - Reserved * &#x60;disabled&#x60; - Disabled * &#x60;deprecated&#x60; - Deprecated | [optional] 
**Vlan** | [**NestedVLANRequest**](NestedVLANRequest.md) |  | [optional] 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**AuthType** | **String** | * &#x60;open&#x60; - Open * &#x60;wep&#x60; - WEP * &#x60;wpa-personal&#x60; - WPA Personal (PSK) * &#x60;wpa-enterprise&#x60; - WPA Enterprise | [optional] 
**AuthCipher** | **String** | * &#x60;auto&#x60; - Auto * &#x60;tkip&#x60; - TKIP * &#x60;aes&#x60; - AES | [optional] 
**AuthPsk** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WirelessLANRequest = Initialize-PSOpenAPIToolsWirelessLANRequest  -Ssid null `
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
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$WirelessLANRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

