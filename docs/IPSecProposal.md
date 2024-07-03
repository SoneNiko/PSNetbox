# IPSecProposal
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**EncryptionAlgorithm** | [**IKEProposalEncryptionAlgorithm**](IKEProposalEncryptionAlgorithm.md) |  | 
**AuthenticationAlgorithm** | [**IKEProposalAuthenticationAlgorithm**](IKEProposalAuthenticationAlgorithm.md) |  | 
**SaLifetimeSeconds** | **Int32** | Security association lifetime (seconds) | [optional] 
**SaLifetimeData** | **Int32** | Security association lifetime (in kilobytes) | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$IPSecProposal = Initialize-PSOpenAPIToolsIPSecProposal  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Description null `
 -EncryptionAlgorithm null `
 -AuthenticationAlgorithm null `
 -SaLifetimeSeconds null `
 -SaLifetimeData null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$IPSecProposal | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

