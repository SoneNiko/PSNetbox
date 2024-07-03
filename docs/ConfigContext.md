# ConfigContext
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
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
**DataSource** | [**NestedDataSource**](NestedDataSource.md) |  | [optional] 
**DataPath** | **String** | Path to remote file (relative to data source root) | [readonly] 
**DataFile** | [**NestedDataFile**](NestedDataFile.md) |  | [readonly] 
**DataSynced** | **System.DateTime** |  | [readonly] 
**VarData** | [**AnyType**](.md) |  | 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$ConfigContext = Initialize-PSOpenAPIToolsConfigContext  -Id null `
 -Url null `
 -Display null `
 -Name null `
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
 -DataPath null `
 -DataFile null `
 -DataSynced null `
 -VarData null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$ConfigContext | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

