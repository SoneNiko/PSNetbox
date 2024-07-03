# WirelessLinkRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InterfaceA** | [**NestedInterfaceRequest**](NestedInterfaceRequest.md) |  | 
**InterfaceB** | [**NestedInterfaceRequest**](NestedInterfaceRequest.md) |  | 
**Ssid** | **String** |  | [optional] 
**Status** | **String** | * &#x60;connected&#x60; - Connected * &#x60;planned&#x60; - Planned * &#x60;decommissioning&#x60; - Decommissioning | [optional] 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**AuthType** | **String** | * &#x60;open&#x60; - Open * &#x60;wep&#x60; - WEP * &#x60;wpa-personal&#x60; - WPA Personal (PSK) * &#x60;wpa-enterprise&#x60; - WPA Enterprise | [optional] 
**AuthCipher** | **String** | * &#x60;auto&#x60; - Auto * &#x60;tkip&#x60; - TKIP * &#x60;aes&#x60; - AES | [optional] 
**AuthPsk** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WirelessLinkRequest = Initialize-PSOpenAPIToolsWirelessLinkRequest  -InterfaceA null `
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
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$WirelessLinkRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

