# VRF
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Rd** | **String** | Unique route distinguisher (as defined in RFC 4364) | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**EnforceUnique** | **Boolean** | Prevent duplicate prefixes/IP addresses within this VRF | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**ImportTargets** | **Int32[]** |  | [optional] 
**ExportTargets** | **Int32[]** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**IpaddressCount** | **Int32** |  | [readonly] 
**PrefixCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$VRF = Initialize-PSOpenAPIToolsVRF  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Rd null `
 -Tenant null `
 -EnforceUnique null `
 -Description null `
 -Comments null `
 -ImportTargets null `
 -ExportTargets null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -IpaddressCount null `
 -PrefixCount null
```

- Convert the resource to JSON
```powershell
$VRF | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

