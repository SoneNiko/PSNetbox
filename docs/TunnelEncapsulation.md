# TunnelEncapsulation
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;ipsec-transport&#x60; - IPsec - Transport * &#x60;ipsec-tunnel&#x60; - IPsec - Tunnel * &#x60;ip-ip&#x60; - IP-in-IP * &#x60;gre&#x60; - GRE | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$TunnelEncapsulation = Initialize-PSOpenAPIToolsTunnelEncapsulation  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$TunnelEncapsulation | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

