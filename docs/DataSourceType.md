# DataSourceType
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **String** | * &#x60;None&#x60; - --------- * &#x60;local&#x60; - Local * &#x60;git&#x60; - Git * &#x60;amazon-s3&#x60; - Amazon S3 | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$DataSourceType = Initialize-PSOpenAPIToolsDataSourceType  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$DataSourceType | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

