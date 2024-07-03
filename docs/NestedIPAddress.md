# NestedIPAddress
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Family** | **Int32** |  | [readonly] 
**Address** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$NestedIPAddress = Initialize-PSOpenAPIToolsNestedIPAddress  -Id null `
 -Url null `
 -Display null `
 -Family null `
 -Address null
```

- Convert the resource to JSON
```powershell
$NestedIPAddress | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

