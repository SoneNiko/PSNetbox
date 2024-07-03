# Service
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Device** | [**NestedDevice**](NestedDevice.md) |  | [optional] 
**VirtualMachine** | [**NestedVirtualMachine**](NestedVirtualMachine.md) |  | [optional] 
**Name** | **String** |  | 
**Ports** | **Int32[]** |  | 
**Protocol** | [**ServiceProtocol**](ServiceProtocol.md) |  | [optional] 
**Ipaddresses** | **Int32[]** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Service = Initialize-PSOpenAPIToolsService  -Id null `
 -Url null `
 -Display null `
 -Device null `
 -VirtualMachine null `
 -Name null `
 -Ports null `
 -Protocol null `
 -Ipaddresses null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$Service | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

