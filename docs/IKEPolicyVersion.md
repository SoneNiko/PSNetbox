# IKEPolicyVersion
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **Int32** | * &#x60;1&#x60; - IKEv1 * &#x60;2&#x60; - IKEv2 | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$IKEPolicyVersion = Initialize-PSOpenAPIToolsIKEPolicyVersion  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$IKEPolicyVersion | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

