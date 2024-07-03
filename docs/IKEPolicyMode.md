# IKEPolicyMode
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;aggressive&#x60; - Aggressive * &#x60;main&#x60; - Main | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$IKEPolicyMode = Initialize-PSOpenAPIToolsIKEPolicyMode  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$IKEPolicyMode | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

