# PatchedWritableRackReservationRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Rack** | **Int32** |  | [optional] 
**Units** | **Int32[]** |  | [optional] 
**User** | **Int32** |  | [optional] 
**Tenant** | **Int32** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableRackReservationRequest = Initialize-PSOpenAPIToolsPatchedWritableRackReservationRequest  -Rack null `
 -Units null `
 -User null `
 -Tenant null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableRackReservationRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

