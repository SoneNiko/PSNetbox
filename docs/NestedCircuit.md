# NestedCircuit
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Cid** | **String** | Unique circuit ID | 

## Examples

- Prepare the resource
```powershell
$NestedCircuit = Initialize-PSOpenAPIToolsNestedCircuit  -Id null `
 -Url null `
 -Display null `
 -Cid null
```

- Convert the resource to JSON
```powershell
$NestedCircuit | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

