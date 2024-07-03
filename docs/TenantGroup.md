# TenantGroup
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Parent** | [**NestedTenantGroup**](NestedTenantGroup.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**TenantCount** | **Int32** |  | [readonly] 
**Depth** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$TenantGroup = Initialize-PSOpenAPIToolsTenantGroup  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null `
 -Parent null `
 -Description null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -TenantCount null `
 -Depth null
```

- Convert the resource to JSON
```powershell
$TenantGroup | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

