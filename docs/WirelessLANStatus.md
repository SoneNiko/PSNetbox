# WirelessLANStatus
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;active&#x60; - Active * &#x60;reserved&#x60; - Reserved * &#x60;disabled&#x60; - Disabled * &#x60;deprecated&#x60; - Deprecated | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WirelessLANStatus = Initialize-PSOpenAPIToolsWirelessLANStatus  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$WirelessLANStatus | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

