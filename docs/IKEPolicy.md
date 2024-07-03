# IKEPolicy
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**Version** | [**IKEPolicyVersion**](IKEPolicyVersion.md) |  | 
**Mode** | [**IKEPolicyMode**](IKEPolicyMode.md) |  | 
**Proposals** | **Int32[]** |  | [optional] 
**PresharedKey** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$IKEPolicy = Initialize-PSOpenAPIToolsIKEPolicy  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Description null `
 -Version null `
 -Mode null `
 -Proposals null `
 -PresharedKey null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$IKEPolicy | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

