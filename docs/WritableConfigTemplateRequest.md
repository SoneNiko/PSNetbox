# WritableConfigTemplateRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**EnvironmentParams** | [**AnyType**](.md) | Any &lt;a href&#x3D;&quot;&quot;https://jinja.palletsprojects.com/en/3.1.x/api/#jinja2.Environment&quot;&quot;&gt;additional parameters&lt;/a&gt; to pass when constructing the Jinja2 environment. | [optional] 
**TemplateCode** | **String** | Jinja2 template code. | 
**DataSource** | **Int32** | Remote data source | [optional] 
**DataFile** | **Int32** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableConfigTemplateRequest = Initialize-PSOpenAPIToolsWritableConfigTemplateRequest  -Name null `
 -Description null `
 -EnvironmentParams null `
 -TemplateCode null `
 -DataSource null `
 -DataFile null `
 -Tags null
```

- Convert the resource to JSON
```powershell
$WritableConfigTemplateRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

