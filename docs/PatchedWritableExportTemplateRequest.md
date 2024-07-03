# PatchedWritableExportTemplateRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentTypes** | **String[]** |  | [optional] 
**Name** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**TemplateCode** | **String** | Jinja2 template code. The list of objects being exported is passed as a context variable named &lt;code&gt;queryset&lt;/code&gt;. | [optional] 
**MimeType** | **String** | Defaults to &lt;code&gt;text/plain; charset&#x3D;utf-8&lt;/code&gt; | [optional] 
**FileExtension** | **String** | Extension to append to the rendered filename | [optional] 
**AsAttachment** | **Boolean** | Download file as attachment | [optional] 
**DataSource** | **Int32** | Remote data source | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableExportTemplateRequest = Initialize-PSOpenAPIToolsPatchedWritableExportTemplateRequest  -ContentTypes null `
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
$PatchedWritableExportTemplateRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

