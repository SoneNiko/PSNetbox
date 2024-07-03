# NestedDevice
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$NestedDevice = Initialize-PSOpenAPIToolsNestedDevice  -Id null `
 -Url null `
 -Display null `
 -Name null
```

- Convert the resource to JSON
```powershell
$NestedDevice | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

