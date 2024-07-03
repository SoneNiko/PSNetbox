# WritableIPSecProposalRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**EncryptionAlgorithm** | **String** | * &#x60;aes-128-cbc&#x60; - 128-bit AES (CBC) * &#x60;aes-128-gcm&#x60; - 128-bit AES (GCM) * &#x60;aes-192-cbc&#x60; - 192-bit AES (CBC) * &#x60;aes-192-gcm&#x60; - 192-bit AES (GCM) * &#x60;aes-256-cbc&#x60; - 256-bit AES (CBC) * &#x60;aes-256-gcm&#x60; - 256-bit AES (GCM) * &#x60;3des-cbc&#x60; - 3DES * &#x60;des-cbc&#x60; - DES | [optional] 
**AuthenticationAlgorithm** | **String** | * &#x60;hmac-sha1&#x60; - SHA-1 HMAC * &#x60;hmac-sha256&#x60; - SHA-256 HMAC * &#x60;hmac-sha384&#x60; - SHA-384 HMAC * &#x60;hmac-sha512&#x60; - SHA-512 HMAC * &#x60;hmac-md5&#x60; - MD5 HMAC | [optional] 
**SaLifetimeSeconds** | **Int32** | Security association lifetime (seconds) | [optional] 
**SaLifetimeData** | **Int32** | Security association lifetime (in kilobytes) | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableIPSecProposalRequest = Initialize-PSOpenAPIToolsWritableIPSecProposalRequest  -Name null `
 -Description null `
 -EncryptionAlgorithm null `
 -AuthenticationAlgorithm null `
 -SaLifetimeSeconds null `
 -SaLifetimeData null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$WritableIPSecProposalRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

