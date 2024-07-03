# ContactRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Group** | [**NestedContactGroupRequest**](NestedContactGroupRequest.md) |  | [optional] 
**Name** | **String** |  | 
**Title** | **String** |  | [optional] 
**Phone** | **String** |  | [optional] 
**Email** | **String** |  | [optional] 
**Address** | **String** |  | [optional] 
**Link** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$ContactRequest = Initialize-PSOpenAPIToolsContactRequest  -Group null `
 -Name null `
 -Title null `
 -Phone null `
 -Email null `
 -Address null `
 -Link null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$ContactRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

