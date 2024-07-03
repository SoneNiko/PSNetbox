# Tag
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Color** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**ObjectTypes** | **String[]** |  | [optional] 
**TaggedItems** | **Int32** |  | [readonly] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Tag = Initialize-PSOpenAPIToolsTag  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null `
 -Color null `
 -Description null `
 -ObjectTypes null `
 -TaggedItems null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$Tag | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

