# WirelessLANAuthType
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;open&#x60; - Open * &#x60;wep&#x60; - WEP * &#x60;wpa-personal&#x60; - WPA Personal (PSK) * &#x60;wpa-enterprise&#x60; - WPA Enterprise | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WirelessLANAuthType = Initialize-PSOpenAPIToolsWirelessLANAuthType  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$WirelessLANAuthType | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

