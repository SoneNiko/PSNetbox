# WirelessLANAuthCipher
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;auto&#x60; - Auto * &#x60;tkip&#x60; - TKIP * &#x60;aes&#x60; - AES | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WirelessLANAuthCipher = Initialize-PSOpenAPIToolsWirelessLANAuthCipher  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$WirelessLANAuthCipher | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

