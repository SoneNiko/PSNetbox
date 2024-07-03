# VirtualChassis
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Domain** | **String** |  | [optional] 
**Master** | [**NestedDevice**](NestedDevice.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**MemberCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$VirtualChassis = Initialize-PSOpenAPIToolsVirtualChassis  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Domain null `
 -Master null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -MemberCount null
```

- Convert the resource to JSON
```powershell
$VirtualChassis | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

