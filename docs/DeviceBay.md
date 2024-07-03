# DeviceBay
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Device** | [**NestedDevice**](NestedDevice.md) |  | 
**Name** | **String** |  | 
**Label** | **String** | Physical label | [optional] 
**Description** | **String** |  | [optional] 
**InstalledDevice** | [**NestedDevice**](NestedDevice.md) |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$DeviceBay = Initialize-PSOpenAPIToolsDeviceBay  -Id null `
 -Url null `
 -Display null `
 -Device null `
 -Name null `
 -Label null `
 -Description null `
 -InstalledDevice null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$DeviceBay | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

