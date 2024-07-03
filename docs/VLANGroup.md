# VLANGroup
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**ScopeType** | **String** |  | [optional] 
**ScopeId** | **Int32** |  | [optional] 
**Scope** | [**AnyType**](.md) |  | [readonly] 
**MinVid** | **Int32** | Lowest permissible ID of a child VLAN | [optional] 
**MaxVid** | **Int32** | Highest permissible ID of a child VLAN | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**VlanCount** | **Int32** |  | [readonly] 
**Utilization** | **String** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$VLANGroup = Initialize-PSOpenAPIToolsVLANGroup  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null `
 -ScopeType null `
 -ScopeId null `
 -Scope null `
 -MinVid null `
 -MaxVid null `
 -Description null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -VlanCount null `
 -Utilization null
```

- Convert the resource to JSON
```powershell
$VLANGroup | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

