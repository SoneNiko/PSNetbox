# ServiceProtocol
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;tcp&#x60; - TCP * &#x60;udp&#x60; - UDP * &#x60;sctp&#x60; - SCTP | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$ServiceProtocol = Initialize-PSOpenAPIToolsServiceProtocol  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$ServiceProtocol | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

