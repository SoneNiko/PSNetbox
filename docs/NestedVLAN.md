# NestedVLAN
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Vid** | **Int32** | Numeric VLAN ID (1-4094) | 
**Name** | **String** |  | 

## Examples

- Prepare the resource
```powershell
$NestedVLAN = Initialize-PSOpenAPIToolsNestedVLAN  -Id null `
 -Url null `
 -Display null `
 -Vid null `
 -Name null
```

- Convert the resource to JSON
```powershell
$NestedVLAN | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

