# IPAddress
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Family** | [**AggregateFamily**](AggregateFamily.md) |  | 
**Address** | **String** |  | 
**Vrf** | [**NestedVRF**](NestedVRF.md) |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Status** | [**IPAddressStatus**](IPAddressStatus.md) |  | [optional] 
**Role** | [**IPAddressRole**](IPAddressRole.md) |  | [optional] 
**AssignedObjectType** | **String** |  | [optional] 
**AssignedObjectId** | **Int64** |  | [optional] 
**AssignedObject** | [**AnyType**](.md) |  | [readonly] 
**NatInside** | [**NestedIPAddress**](NestedIPAddress.md) |  | [optional] 
**NatOutside** | [**NestedIPAddress[]**](NestedIPAddress.md) |  | [readonly] 
**DnsName** | **String** | Hostname or FQDN (not case-sensitive) | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$IPAddress = Initialize-PSOpenAPIToolsIPAddress  -Id null `
 -Url null `
 -Display null `
 -Family null `
 -Address null `
 -Vrf null `
 -Tenant null `
 -Status null `
 -Role null `
 -AssignedObjectType null `
 -AssignedObjectId null `
 -AssignedObject null `
 -NatInside null `
 -NatOutside null `
 -DnsName null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$IPAddress | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

