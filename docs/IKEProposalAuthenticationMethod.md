# IKEProposalAuthenticationMethod
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;preshared-keys&#x60; - Pre-shared keys * &#x60;certificates&#x60; - Certificates * &#x60;rsa-signatures&#x60; - RSA signatures * &#x60;dsa-signatures&#x60; - DSA signatures | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$IKEProposalAuthenticationMethod = Initialize-PSOpenAPIToolsIKEProposalAuthenticationMethod  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$IKEProposalAuthenticationMethod | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

