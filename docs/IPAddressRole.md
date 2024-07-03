# IPAddressRole
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;loopback&#x60; - Loopback * &#x60;secondary&#x60; - Secondary * &#x60;anycast&#x60; - Anycast * &#x60;vip&#x60; - VIP * &#x60;vrrp&#x60; - VRRP * &#x60;hsrp&#x60; - HSRP * &#x60;glbp&#x60; - GLBP * &#x60;carp&#x60; - CARP | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$IPAddressRole = Initialize-PSOpenAPIToolsIPAddressRole  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$IPAddressRole | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

