# PatchedCustomLinkRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentTypes** | **String[]** |  | [optional] 
**Name** | **String** |  | [optional] 
**Enabled** | **Boolean** |  | [optional] 
**LinkText** | **String** | Jinja2 template code for link text | [optional] 
**LinkUrl** | **String** | Jinja2 template code for link URL | [optional] 
**Weight** | **Int32** |  | [optional] 
**GroupName** | **String** | Links with the same group will appear as a dropdown menu | [optional] 
**ButtonClass** | **String** | The class of the first link in a group will be used for the dropdown button  * &#x60;outline-dark&#x60; - Default * &#x60;blue&#x60; - Blue * &#x60;indigo&#x60; - Indigo * &#x60;purple&#x60; - Purple * &#x60;pink&#x60; - Pink * &#x60;red&#x60; - Red * &#x60;orange&#x60; - Orange * &#x60;yellow&#x60; - Yellow * &#x60;green&#x60; - Green * &#x60;teal&#x60; - Teal * &#x60;cyan&#x60; - Cyan * &#x60;gray&#x60; - Gray * &#x60;black&#x60; - Black * &#x60;white&#x60; - White * &#x60;ghost-dark&#x60; - Link | [optional] 
**NewWindow** | **Boolean** | Force link to open in a new window | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedCustomLinkRequest = Initialize-PSOpenAPIToolsPatchedCustomLinkRequest  -ContentTypes null `
 -Name null `
 -Enabled null `
 -LinkText null `
 -LinkUrl null `
 -Weight null `
 -GroupName null `
 -ButtonClass null `
 -NewWindow null
```

- Convert the resource to JSON
```powershell
$PatchedCustomLinkRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

