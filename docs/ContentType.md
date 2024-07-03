# ContentType
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**AppLabel** | **String** |  | 
**Model** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$ContentType = Initialize-PSOpenAPIToolsContentType  -Id null `
 -Url null `
 -Display null `
 -AppLabel null `
 -Model null
```

- Convert the resource to JSON
```powershell
$ContentType | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

