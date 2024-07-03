# IPAddressRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | **String** |  | 
**Vrf** | [**NestedVRFRequest**](NestedVRFRequest.md) |  | [optional] 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**Status** | **String** | * &#x60;active&#x60; - Active * &#x60;reserved&#x60; - Reserved * &#x60;deprecated&#x60; - Deprecated * &#x60;dhcp&#x60; - DHCP * &#x60;slaac&#x60; - SLAAC | [optional] 
**Role** | **String** | * &#x60;loopback&#x60; - Loopback * &#x60;secondary&#x60; - Secondary * &#x60;anycast&#x60; - Anycast * &#x60;vip&#x60; - VIP * &#x60;vrrp&#x60; - VRRP * &#x60;hsrp&#x60; - HSRP * &#x60;glbp&#x60; - GLBP * &#x60;carp&#x60; - CARP | [optional] 
**AssignedObjectType** | **String** |  | [optional] 
**AssignedObjectId** | **Int64** |  | [optional] 
**NatInside** | [**NestedIPAddressRequest**](NestedIPAddressRequest.md) |  | [optional] 
**DnsName** | **String** | Hostname or FQDN (not case-sensitive) | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$IPAddressRequest = Initialize-PSOpenAPIToolsIPAddressRequest  -Address null `
 -Vrf null `
 -Tenant null `
 -Status null `
 -Role null `
 -AssignedObjectType null `
 -AssignedObjectId null `
 -NatInside null `
 -DnsName null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$IPAddressRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

