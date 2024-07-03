# VirtualDeviceContext
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Device** | [**NestedDevice**](NestedDevice.md) |  | 
**Identifier** | **Int32** | Numeric identifier unique to the parent device | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**PrimaryIp** | [**NestedIPAddress**](NestedIPAddress.md) |  | [readonly] 
**PrimaryIp4** | [**NestedIPAddress**](NestedIPAddress.md) |  | [optional] 
**PrimaryIp6** | [**NestedIPAddress**](NestedIPAddress.md) |  | [optional] 
**Status** | [**VirtualDeviceContextStatus**](VirtualDeviceContextStatus.md) |  | 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**InterfaceCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$VirtualDeviceContext = Initialize-PSOpenAPIToolsVirtualDeviceContext  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Device null `
 -Identifier null `
 -Tenant null `
 -PrimaryIp null `
 -PrimaryIp4 null `
 -PrimaryIp6 null `
 -Status null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -InterfaceCount null
```

- Convert the resource to JSON
```powershell
$VirtualDeviceContext | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

