# IKEProposalAuthenticationAlgorithm
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;hmac-sha1&#x60; - SHA-1 HMAC * &#x60;hmac-sha256&#x60; - SHA-256 HMAC * &#x60;hmac-sha384&#x60; - SHA-384 HMAC * &#x60;hmac-sha512&#x60; - SHA-512 HMAC * &#x60;hmac-md5&#x60; - MD5 HMAC | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$IKEProposalAuthenticationAlgorithm = Initialize-PSOpenAPIToolsIKEProposalAuthenticationAlgorithm  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$IKEProposalAuthenticationAlgorithm | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

