# FrontPortRearPort
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Label** | **String** | Physical label | [optional] 
**Description** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$FrontPortRearPort = Initialize-PSOpenAPIToolsFrontPortRearPort  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Label null `
 -Description null
```

- Convert the resource to JSON
```powershell
$FrontPortRearPort | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

