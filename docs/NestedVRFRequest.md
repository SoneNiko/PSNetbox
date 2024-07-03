# NestedVRFRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Rd** | **String** | Unique route distinguisher (as defined in RFC 4364) | [optional] 

## Examples

- Prepare the resource
```powershell
$NestedVRFRequest = Initialize-PSOpenAPIToolsNestedVRFRequest  -Name null `
 -Rd null
```

- Convert the resource to JSON
```powershell
$NestedVRFRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

