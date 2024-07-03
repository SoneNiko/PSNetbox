# DataSource
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Type** | [**DataSourceType**](DataSourceType.md) |  | 
**SourceUrl** | **String** |  | 
**Enabled** | **Boolean** |  | [optional] 
**Status** | [**DataSourceStatus**](DataSourceStatus.md) |  | 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Parameters** | [**AnyType**](.md) |  | [optional] 
**IgnoreRules** | **String** | Patterns (one per line) matching files to ignore when syncing | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**FileCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$DataSource = Initialize-PSOpenAPIToolsDataSource  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Type null `
 -SourceUrl null `
 -Enabled null `
 -Status null `
 -Description null `
 -Comments null `
 -Parameters null `
 -IgnoreRules null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -FileCount null
```

- Convert the resource to JSON
```powershell
$DataSource | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

