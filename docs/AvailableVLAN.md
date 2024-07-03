# AvailableVLAN
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Vid** | **Int32** |  | [readonly] 
**Group** | [**NestedVLANGroup**](NestedVLANGroup.md) |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$AvailableVLAN = Initialize-PSOpenAPIToolsAvailableVLAN  -Vid null `
 -Group null
```

- Convert the resource to JSON
```powershell
$AvailableVLAN | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

