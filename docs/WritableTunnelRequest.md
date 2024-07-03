# WritableTunnelRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Status** | **String** | * &#x60;planned&#x60; - Planned * &#x60;active&#x60; - Active * &#x60;disabled&#x60; - Disabled | [optional] 
**Group** | **Int32** |  | [optional] 
**Encapsulation** | **String** | * &#x60;ipsec-transport&#x60; - IPsec - Transport * &#x60;ipsec-tunnel&#x60; - IPsec - Tunnel * &#x60;ip-ip&#x60; - IP-in-IP * &#x60;gre&#x60; - GRE | 
**IpsecProfile** | **Int32** |  | [optional] 
**Tenant** | **Int32** |  | [optional] 
**TunnelId** | **Int64** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableTunnelRequest = Initialize-PSOpenAPIToolsWritableTunnelRequest  -Name null `
 -Status null `
 -Group null `
 -Encapsulation null `
 -IpsecProfile null `
 -Tenant null `
 -TunnelId null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$WritableTunnelRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

