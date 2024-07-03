# WritableCircuitRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cid** | **String** | Unique circuit ID | 
**Provider** | **Int32** |  | 
**ProviderAccount** | **Int32** |  | [optional] 
**Type** | **Int32** |  | 
**Status** | **String** | * &#x60;planned&#x60; - Planned * &#x60;provisioning&#x60; - Provisioning * &#x60;active&#x60; - Active * &#x60;offline&#x60; - Offline * &#x60;deprovisioning&#x60; - Deprovisioning * &#x60;decommissioned&#x60; - Decommissioned | [optional] 
**Tenant** | **Int32** |  | [optional] 
**InstallDate** | **System.DateTime** |  | [optional] 
**TerminationDate** | **System.DateTime** |  | [optional] 
**CommitRate** | **Int32** | Committed rate | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableCircuitRequest = Initialize-PSOpenAPIToolsWritableCircuitRequest  -Cid null `
 -Provider null `
 -ProviderAccount null `
 -Type null `
 -Status null `
 -Tenant null `
 -InstallDate null `
 -TerminationDate null `
 -CommitRate null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$WritableCircuitRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

