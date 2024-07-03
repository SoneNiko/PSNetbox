# DeviceRole
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Color** | **String** |  | [optional] 
**VmRole** | **Boolean** | Virtual machines may be assigned to this role | [optional] 
**ConfigTemplate** | [**NestedConfigTemplate**](NestedConfigTemplate.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**DeviceCount** | **Int32** |  | [readonly] 
**VirtualmachineCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$DeviceRole = Initialize-PSOpenAPIToolsDeviceRole  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null `
 -Color null `
 -VmRole null `
 -ConfigTemplate null `
 -Description null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -DeviceCount null `
 -VirtualmachineCount null
```

- Convert the resource to JSON
```powershell
$DeviceRole | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

