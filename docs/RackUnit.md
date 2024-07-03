# RackUnit
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Double** |  | [readonly] 
**Name** | **String** |  | [readonly] 
**Face** | [**RackUnitFace**](RackUnitFace.md) |  | 
**Device** | [**NestedDevice**](NestedDevice.md) |  | [readonly] 
**Occupied** | **Boolean** |  | [readonly] 
**Display** | **String** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$RackUnit = Initialize-PSOpenAPIToolsRackUnit  -Id null `
 -Name null `
 -Face null `
 -Device null `
 -Occupied null `
 -Display null
```

- Convert the resource to JSON
```powershell
$RackUnit | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

