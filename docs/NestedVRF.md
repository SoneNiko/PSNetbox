# NestedVRF
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Rd** | **String** | Unique route distinguisher (as defined in RFC 4364) | [optional] 

## Examples

- Prepare the resource
```powershell
$NestedVRF = Initialize-PSOpenAPIToolsNestedVRF  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Rd null
```

- Convert the resource to JSON
```powershell
$NestedVRF | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

