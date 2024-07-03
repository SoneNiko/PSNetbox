# Webhook
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**PayloadUrl** | **String** | This URL will be called using the HTTP method defined when the webhook is called. Jinja2 template processing is supported with the same context as the request body. | 
**HttpMethod** | **String** | * &#x60;GET&#x60; - GET * &#x60;POST&#x60; - POST * &#x60;PUT&#x60; - PUT * &#x60;PATCH&#x60; - PATCH * &#x60;DELETE&#x60; - DELETE | [optional] 
**HttpContentType** | **String** | The complete list of official content types is available &lt;a href&#x3D;&quot;&quot;https://www.iana.org/assignments/media-types/media-types.xhtml&quot;&quot;&gt;here&lt;/a&gt;. | [optional] 
**AdditionalHeaders** | **String** | User-supplied HTTP headers to be sent with the request in addition to the HTTP content type. Headers should be defined in the format &lt;code&gt;Name: Value&lt;/code&gt;. Jinja2 template processing is supported with the same context as the request body (below). | [optional] 
**BodyTemplate** | **String** | Jinja2 template for a custom request body. If blank, a JSON object representing the change will be included. Available context data includes: &lt;code&gt;event&lt;/code&gt;, &lt;code&gt;model&lt;/code&gt;, &lt;code&gt;timestamp&lt;/code&gt;, &lt;code&gt;username&lt;/code&gt;, &lt;code&gt;request_id&lt;/code&gt;, and &lt;code&gt;data&lt;/code&gt;. | [optional] 
**Secret** | **String** | When provided, the request will include a &lt;code&gt;X-Hook-Signature&lt;/code&gt; header containing a HMAC hex digest of the payload body using the secret as the key. The secret is not transmitted in the request. | [optional] 
**SslVerification** | **Boolean** | Enable SSL certificate verification. Disable with caution! | [optional] 
**CaFilePath** | **String** | The specific CA certificate file to use for SSL verification. Leave blank to use the system defaults. | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Webhook = Initialize-PSOpenAPIToolsWebhook  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Description null `
 -PayloadUrl null `
 -HttpMethod null `
 -HttpContentType null `
 -AdditionalHeaders null `
 -BodyTemplate null `
 -Secret null `
 -SslVerification null `
 -CaFilePath null `
 -CustomFields null `
 -Tags null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$Webhook | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

