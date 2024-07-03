# ExportTemplateRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentTypes** | **String[]** |  | 
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**TemplateCode** | **String** | Jinja2 template code. The list of objects being exported is passed as a context variable named &lt;code&gt;queryset&lt;/code&gt;. | 
**MimeType** | **String** | Defaults to &lt;code&gt;text/plain; charset&#x3D;utf-8&lt;/code&gt; | [optional] 
**FileExtension** | **String** | Extension to append to the rendered filename | [optional] 
**AsAttachment** | **Boolean** | Download file as attachment | [optional] 
**DataSource** | [**NestedDataSourceRequest**](NestedDataSourceRequest.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$ExportTemplateRequest = Initialize-PSOpenAPIToolsExportTemplateRequest  -ContentTypes null `
 -Name null `
 -Description null `
 -TemplateCode null `
 -MimeType null `
 -FileExtension null `
 -AsAttachment null `
 -DataSource null
```

- Convert the resource to JSON
```powershell
$ExportTemplateRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

