# L2VPNTermination
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**L2vpn** | [**NestedL2VPN**](NestedL2VPN.md) |  | 
**AssignedObjectType** | **String** |  | 
**AssignedObjectId** | **Int64** |  | 
**AssignedObject** | [**AnyType**](.md) |  | [readonly] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$L2VPNTermination = Initialize-PSOpenAPIToolsL2VPNTermination  -Id null `
 -Url null `
 -Display null `
 -L2vpn null `
 -AssignedObjectType null `
 -AssignedObjectId null `
 -AssignedObject null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$L2VPNTermination | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

