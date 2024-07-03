# WritableConfigContextRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Weight** | **Int32** |  | [optional] 
**Description** | **String** |  | [optional] 
**IsActive** | **Boolean** |  | [optional] 
**Regions** | **Int32[]** |  | [optional] 
**SiteGroups** | **Int32[]** |  | [optional] 
**Sites** | **Int32[]** |  | [optional] 
**Locations** | **Int32[]** |  | [optional] 
**DeviceTypes** | **Int32[]** |  | [optional] 
**Roles** | **Int32[]** |  | [optional] 
**Platforms** | **Int32[]** |  | [optional] 
**ClusterTypes** | **Int32[]** |  | [optional] 
**ClusterGroups** | **Int32[]** |  | [optional] 
**Clusters** | **Int32[]** |  | [optional] 
**TenantGroups** | **Int32[]** |  | [optional] 
**Tenants** | **Int32[]** |  | [optional] 
**Tags** | **String[]** |  | [optional] 
**DataSource** | **Int32** | Remote data source | [optional] 
**VarData** | [**AnyType**](.md) |  | 

## Examples

- Prepare the resource
```powershell
$WritableConfigContextRequest = Initialize-PSOpenAPIToolsWritableConfigContextRequest  -Name null `
 -Weight null `
 -Description null `
 -IsActive null `
 -Regions null `
 -SiteGroups null `
 -Sites null `
 -Locations null `
 -DeviceTypes null `
 -Roles null `
 -Platforms null `
 -ClusterTypes null `
 -ClusterGroups null `
 -Clusters null `
 -TenantGroups null `
 -Tenants null `
 -Tags null `
 -DataSource null `
 -VarData null
```

- Convert the resource to JSON
```powershell
$WritableConfigContextRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

