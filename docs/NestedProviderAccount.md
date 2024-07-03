# NestedProviderAccount
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | [optional] 
**Account** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$NestedProviderAccount = Initialize-PSOpenAPIToolsNestedProviderAccount  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Account null
```

- Convert the resource to JSON
```powershell
$NestedProviderAccount | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

