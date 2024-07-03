# IKEProposal
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**AuthenticationMethod** | [**IKEProposalAuthenticationMethod**](IKEProposalAuthenticationMethod.md) |  | 
**EncryptionAlgorithm** | [**IKEProposalEncryptionAlgorithm**](IKEProposalEncryptionAlgorithm.md) |  | 
**AuthenticationAlgorithm** | [**IKEProposalAuthenticationAlgorithm**](IKEProposalAuthenticationAlgorithm.md) |  | 
**Group** | [**IKEProposalGroup**](IKEProposalGroup.md) |  | 
**SaLifetime** | **Int32** | Security association lifetime (in seconds) | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$IKEProposal = Initialize-PSOpenAPIToolsIKEProposal  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Description null `
 -AuthenticationMethod null `
 -EncryptionAlgorithm null `
 -AuthenticationAlgorithm null `
 -Group null `
 -SaLifetime null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$IKEProposal | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

