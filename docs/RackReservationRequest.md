# RackReservationRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Rack** | [**NestedRackRequest**](NestedRackRequest.md) |  | 
**Units** | **Int32[]** |  | 
**User** | [**NestedUserRequest**](NestedUserRequest.md) |  | 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**Description** | **String** |  | 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$RackReservationRequest = Initialize-PSOpenAPIToolsRackReservationRequest  -Rack null `
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
$RackReservationRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

