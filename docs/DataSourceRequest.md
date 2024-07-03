# DataSourceRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Type** | **String** | * &#x60;None&#x60; - --------- * &#x60;local&#x60; - Local * &#x60;git&#x60; - Git * &#x60;amazon-s3&#x60; - Amazon S3 | 
**SourceUrl** | **String** |  | 
**Enabled** | **Boolean** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Parameters** | [**AnyType**](.md) |  | [optional] 
**IgnoreRules** | **String** | Patterns (one per line) matching files to ignore when syncing | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$DataSourceRequest = Initialize-PSOpenAPIToolsDataSourceRequest  -Name null `
 -Type null `
 -SourceUrl null `
 -Enabled null `
 -Description null `
 -Comments null `
 -Parameters null `
 -IgnoreRules null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$DataSourceRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

