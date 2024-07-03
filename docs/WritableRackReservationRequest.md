# WritableRackReservationRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Rack** | **Int32** |  | 
**Units** | **Int32[]** |  | 
**User** | **Int32** |  | 
**Tenant** | **Int32** |  | [optional] 
**Description** | **String** |  | 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableRackReservationRequest = Initialize-PSOpenAPIToolsWritableRackReservationRequest  -Rack null `
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
$WritableRackReservationRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

