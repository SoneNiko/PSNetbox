# ConfigTemplate
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**EnvironmentParams** | [**AnyType**](.md) | Any &lt;a href&#x3D;&quot;&quot;https://jinja.palletsprojects.com/en/3.1.x/api/#jinja2.Environment&quot;&quot;&gt;additional parameters&lt;/a&gt; to pass when constructing the Jinja2 environment. | [optional] 
**TemplateCode** | **String** | Jinja2 template code. | 
**DataSource** | [**NestedDataSource**](NestedDataSource.md) |  | [optional] 
**DataPath** | **String** | Path to remote file (relative to data source root) | [readonly] 
**DataFile** | [**NestedDataFile**](NestedDataFile.md) |  | [optional] 
**DataSynced** | **System.DateTime** |  | [readonly] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$ConfigTemplate = Initialize-PSOpenAPIToolsConfigTemplate  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Description null `
 -EnvironmentParams null `
 -TemplateCode null `
 -DataSource null `
 -DataPath null `
 -DataFile null `
 -DataSynced null `
 -Tags null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$ConfigTemplate | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

