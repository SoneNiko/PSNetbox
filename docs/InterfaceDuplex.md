# InterfaceDuplex
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;half&#x60; - Half * &#x60;full&#x60; - Full * &#x60;auto&#x60; - Auto | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$InterfaceDuplex = Initialize-PSOpenAPIToolsInterfaceDuplex  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$InterfaceDuplex | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

