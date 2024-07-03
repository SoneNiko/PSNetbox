# NestedUser
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Username** | **String** | Required. 150 characters or fewer. Letters, digits and @/./+/-/_ only. | 

## Examples

- Prepare the resource
```powershell
$NestedUser = Initialize-PSOpenAPIToolsNestedUser  -Id null `
 -Url null `
 -Display null `
 -Username null
```

- Convert the resource to JSON
```powershell
$NestedUser | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

