# IPAddressStatus
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;active&#x60; - Active * &#x60;reserved&#x60; - Reserved * &#x60;deprecated&#x60; - Deprecated * &#x60;dhcp&#x60; - DHCP * &#x60;slaac&#x60; - SLAAC | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$IPAddressStatus = Initialize-PSOpenAPIToolsIPAddressStatus  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$IPAddressStatus | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

