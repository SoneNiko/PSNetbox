# RackReservation
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Rack** | [**NestedRack**](NestedRack.md) |  | 
**Units** | **Int32[]** |  | 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**User** | [**NestedUser**](NestedUser.md) |  | 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Description** | **String** |  | 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$RackReservation = Initialize-PSOpenAPIToolsRackReservation  -Id null `
 -Url null `
 -Display null `
 -Rack null `
 -Units null `
 -Created null `
 -LastUpdated null `
 -User null `
 -Tenant null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$RackReservation | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

