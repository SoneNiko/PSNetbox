# CircuitRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cid** | **String** | Unique circuit ID | 
**Provider** | [**NestedProviderRequest**](NestedProviderRequest.md) |  | 
**ProviderAccount** | [**NestedProviderAccountRequest**](NestedProviderAccountRequest.md) |  | [optional] 
**Type** | [**NestedCircuitTypeRequest**](NestedCircuitTypeRequest.md) |  | 
**Status** | **String** | * &#x60;planned&#x60; - Planned * &#x60;provisioning&#x60; - Provisioning * &#x60;active&#x60; - Active * &#x60;offline&#x60; - Offline * &#x60;deprovisioning&#x60; - Deprovisioning * &#x60;decommissioned&#x60; - Decommissioned | [optional] 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
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
$CircuitRequest = Initialize-PSOpenAPIToolsCircuitRequest  -Cid null `
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
$CircuitRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

