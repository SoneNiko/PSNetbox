# L2VPN
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Identifier** | **Int64** |  | [optional] 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Type** | [**L2VPNType**](L2VPNType.md) |  | [optional] 
**ImportTargets** | **Int32[]** |  | [optional] 
**ExportTargets** | **Int32[]** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$L2VPN = Initialize-PSOpenAPIToolsL2VPN  -Id null `
 -Url null `
 -Display null `
 -Identifier null `
 -Name null `
 -Slug null `
 -Type null `
 -ImportTargets null `
 -ExportTargets null `
 -Description null `
 -Comments null `
 -Tenant null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$L2VPN | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

