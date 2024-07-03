# Group
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**UserCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Group = Initialize-PSOpenAPIToolsGroup  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -UserCount null
```

- Convert the resource to JSON
```powershell
$Group | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

