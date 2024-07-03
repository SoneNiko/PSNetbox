# ClusterRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Type** | [**NestedClusterTypeRequest**](NestedClusterTypeRequest.md) |  | 
**Group** | [**NestedClusterGroupRequest**](NestedClusterGroupRequest.md) |  | [optional] 
**Status** | **String** | * &#x60;planned&#x60; - Planned * &#x60;staging&#x60; - Staging * &#x60;active&#x60; - Active * &#x60;decommissioning&#x60; - Decommissioning * &#x60;offline&#x60; - Offline | [optional] 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**Site** | [**NestedSiteRequest**](NestedSiteRequest.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$ClusterRequest = Initialize-PSOpenAPIToolsClusterRequest  -Name null `
 -Type null `
 -Group null `
 -Status null `
 -Tenant null `
 -Site null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$ClusterRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

