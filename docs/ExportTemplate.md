# ExportTemplate
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**ContentTypes** | **String[]** |  | 
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**TemplateCode** | **String** | Jinja2 template code. The list of objects being exported is passed as a context variable named &lt;code&gt;queryset&lt;/code&gt;. | 
**MimeType** | **String** | Defaults to &lt;code&gt;text/plain; charset&#x3D;utf-8&lt;/code&gt; | [optional] 
**FileExtension** | **String** | Extension to append to the rendered filename | [optional] 
**AsAttachment** | **Boolean** | Download file as attachment | [optional] 
**DataSource** | [**NestedDataSource**](NestedDataSource.md) |  | [optional] 
**DataPath** | **String** | Path to remote file (relative to data source root) | [readonly] 
**DataFile** | [**NestedDataFile**](NestedDataFile.md) |  | [readonly] 
**DataSynced** | **System.DateTime** |  | [readonly] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$ExportTemplate = Initialize-PSOpenAPIToolsExportTemplate  -Id null `
 -Url null `
 -Display null `
 -ContentTypes null `
 -Name null `
 -Description null `
 -TemplateCode null `
 -MimeType null `
 -FileExtension null `
 -AsAttachment null `
 -DataSource null `
 -DataPath null `
 -DataFile null `
 -DataSynced null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$ExportTemplate | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

