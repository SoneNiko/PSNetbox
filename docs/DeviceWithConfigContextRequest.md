# DeviceWithConfigContextRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | [optional] 
**DeviceType** | [**NestedDeviceTypeRequest**](NestedDeviceTypeRequest.md) |  | 
**Role** | [**NestedDeviceRoleRequest**](NestedDeviceRoleRequest.md) |  | 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**Platform** | [**NestedPlatformRequest**](NestedPlatformRequest.md) |  | [optional] 
**Serial** | **String** | Chassis serial number, assigned by the manufacturer | [optional] 
**AssetTag** | **String** | A unique tag used to identify this device | [optional] 
**Site** | [**NestedSiteRequest**](NestedSiteRequest.md) |  | 
**Location** | [**NestedLocationRequest**](NestedLocationRequest.md) |  | [optional] 
**Rack** | [**NestedRackRequest**](NestedRackRequest.md) |  | [optional] 
**Position** | **Double** |  | [optional] 
**Face** | **String** | * &#x60;front&#x60; - Front * &#x60;rear&#x60; - Rear | [optional] 
**Latitude** | **Double** | GPS coordinate in decimal format (xx.yyyyyy) | [optional] 
**Longitude** | **Double** | GPS coordinate in decimal format (xx.yyyyyy) | [optional] 
**Status** | **String** | * &#x60;offline&#x60; - Offline * &#x60;active&#x60; - Active * &#x60;planned&#x60; - Planned * &#x60;staged&#x60; - Staged * &#x60;failed&#x60; - Failed * &#x60;inventory&#x60; - Inventory * &#x60;decommissioning&#x60; - Decommissioning | [optional] 
**Airflow** | **String** | * &#x60;front-to-rear&#x60; - Front to rear * &#x60;rear-to-front&#x60; - Rear to front * &#x60;left-to-right&#x60; - Left to right * &#x60;right-to-left&#x60; - Right to left * &#x60;side-to-rear&#x60; - Side to rear * &#x60;passive&#x60; - Passive * &#x60;mixed&#x60; - Mixed | [optional] 
**PrimaryIp4** | [**NestedIPAddressRequest**](NestedIPAddressRequest.md) |  | [optional] 
**PrimaryIp6** | [**NestedIPAddressRequest**](NestedIPAddressRequest.md) |  | [optional] 
**OobIp** | [**NestedIPAddressRequest**](NestedIPAddressRequest.md) |  | [optional] 
**Cluster** | [**NestedClusterRequest**](NestedClusterRequest.md) |  | [optional] 
**VirtualChassis** | [**NestedVirtualChassisRequest**](NestedVirtualChassisRequest.md) |  | [optional] 
**VcPosition** | **Int32** |  | [optional] 
**VcPriority** | **Int32** | Virtual chassis master election priority | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**ConfigTemplate** | [**NestedConfigTemplateRequest**](NestedConfigTemplateRequest.md) |  | [optional] 
**LocalContextData** | [**AnyType**](.md) | Local config context data takes precedence over source contexts in the final rendered config context | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$DeviceWithConfigContextRequest = Initialize-PSOpenAPIToolsDeviceWithConfigContextRequest  -Name null `
 -DeviceType null `
 -Role null `
 -Tenant null `
 -Platform null `
 -Serial null `
 -AssetTag null `
 -Site null `
 -Location null `
 -Rack null `
 -Position null `
 -Face null `
 -Latitude null `
 -Longitude null `
 -Status null `
 -Airflow null `
 -PrimaryIp4 null `
 -PrimaryIp6 null `
 -OobIp null `
 -Cluster null `
 -VirtualChassis null `
 -VcPosition null `
 -VcPriority null `
 -Description null `
 -Comments null `
 -ConfigTemplate null `
 -LocalContextData null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$DeviceWithConfigContextRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

