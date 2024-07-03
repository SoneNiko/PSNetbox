# Tunnel
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Status** | [**TunnelStatus**](TunnelStatus.md) |  | 
**Group** | [**NestedTunnelGroup**](NestedTunnelGroup.md) |  | [optional] 
**Encapsulation** | [**TunnelEncapsulation**](TunnelEncapsulation.md) |  | 
**IpsecProfile** | [**NestedIPSecProfile**](NestedIPSecProfile.md) |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**TunnelId** | **Int64** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Tunnel = Initialize-PSOpenAPIToolsTunnel  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Status null `
 -Group null `
 -Encapsulation null `
 -IpsecProfile null `
 -Tenant null `
 -TunnelId null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$Tunnel | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

