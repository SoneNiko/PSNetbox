# DeviceWithConfigContext
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | [optional] 
**DeviceType** | [**NestedDeviceType**](NestedDeviceType.md) |  | 
**Role** | [**NestedDeviceRole**](NestedDeviceRole.md) |  | 
**DeviceRole** | [**NestedDeviceRole**](NestedDeviceRole.md) | Deprecated in v3.6 in favor of &#x60;role&#x60;. | [readonly] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Platform** | [**NestedPlatform**](NestedPlatform.md) |  | [optional] 
**Serial** | **String** | Chassis serial number, assigned by the manufacturer | [optional] 
**AssetTag** | **String** | A unique tag used to identify this device | [optional] 
**Site** | [**NestedSite**](NestedSite.md) |  | 
**Location** | [**NestedLocation**](NestedLocation.md) |  | [optional] 
**Rack** | [**NestedRack**](NestedRack.md) |  | [optional] 
**Position** | **Double** |  | [optional] 
**Face** | [**DeviceFace**](DeviceFace.md) |  | [optional] 
**Latitude** | **Double** | GPS coordinate in decimal format (xx.yyyyyy) | [optional] 
**Longitude** | **Double** | GPS coordinate in decimal format (xx.yyyyyy) | [optional] 
**ParentDevice** | [**NestedDevice**](NestedDevice.md) |  | [readonly] 
**Status** | [**DeviceStatus**](DeviceStatus.md) |  | [optional] 
**Airflow** | [**DeviceAirflow**](DeviceAirflow.md) |  | [optional] 
**PrimaryIp** | [**NestedIPAddress**](NestedIPAddress.md) |  | [readonly] 
**PrimaryIp4** | [**NestedIPAddress**](NestedIPAddress.md) |  | [optional] 
**PrimaryIp6** | [**NestedIPAddress**](NestedIPAddress.md) |  | [optional] 
**OobIp** | [**NestedIPAddress**](NestedIPAddress.md) |  | [optional] 
**Cluster** | [**NestedCluster**](NestedCluster.md) |  | [optional] 
**VirtualChassis** | [**NestedVirtualChassis**](NestedVirtualChassis.md) |  | [optional] 
**VcPosition** | **Int32** |  | [optional] 
**VcPriority** | **Int32** | Virtual chassis master election priority | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**ConfigTemplate** | [**NestedConfigTemplate**](NestedConfigTemplate.md) |  | [optional] 
**ConfigContext** | [**AnyType**](.md) |  | [readonly] 
**LocalContextData** | [**AnyType**](.md) | Local config context data takes precedence over source contexts in the final rendered config context | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**ConsolePortCount** | **Int32** |  | [readonly] 
**ConsoleServerPortCount** | **Int32** |  | [readonly] 
**PowerPortCount** | **Int32** |  | [readonly] 
**PowerOutletCount** | **Int32** |  | [readonly] 
**InterfaceCount** | **Int32** |  | [readonly] 
**FrontPortCount** | **Int32** |  | [readonly] 
**RearPortCount** | **Int32** |  | [readonly] 
**DeviceBayCount** | **Int32** |  | [readonly] 
**ModuleBayCount** | **Int32** |  | [readonly] 
**InventoryItemCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$DeviceWithConfigContext = Initialize-PSOpenAPIToolsDeviceWithConfigContext  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -DeviceType null `
 -Role null `
 -DeviceRole null `
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
 -ParentDevice null `
 -Status null `
 -Airflow null `
 -PrimaryIp null `
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
 -ConfigContext null `
 -LocalContextData null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -ConsolePortCount null `
 -ConsoleServerPortCount null `
 -PowerPortCount null `
 -PowerOutletCount null `
 -InterfaceCount null `
 -FrontPortCount null `
 -RearPortCount null `
 -DeviceBayCount null `
 -ModuleBayCount null `
 -InventoryItemCount null
```

- Convert the resource to JSON
```powershell
$DeviceWithConfigContext | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

