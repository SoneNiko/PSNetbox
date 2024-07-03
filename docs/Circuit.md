# Circuit
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Cid** | **String** | Unique circuit ID | 
**Provider** | [**NestedProvider**](NestedProvider.md) |  | 
**ProviderAccount** | [**NestedProviderAccount**](NestedProviderAccount.md) |  | [optional] 
**Type** | [**NestedCircuitType**](NestedCircuitType.md) |  | 
**Status** | [**CircuitStatus**](CircuitStatus.md) |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**InstallDate** | **System.DateTime** |  | [optional] 
**TerminationDate** | **System.DateTime** |  | [optional] 
**CommitRate** | **Int32** | Committed rate | [optional] 
**Description** | **String** |  | [optional] 
**TerminationA** | [**CircuitCircuitTermination**](CircuitCircuitTermination.md) |  | [readonly] 
**TerminationZ** | [**CircuitCircuitTermination**](CircuitCircuitTermination.md) |  | [readonly] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Circuit = Initialize-PSOpenAPIToolsCircuit  -Id null `
 -Url null `
 -Display null `
 -Cid null `
 -Provider null `
 -ProviderAccount null `
 -Type null `
 -Status null `
 -Tenant null `
 -InstallDate null `
 -TerminationDate null `
 -CommitRate null `
 -Description null `
 -TerminationA null `
 -TerminationZ null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$Circuit | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

