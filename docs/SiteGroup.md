# SiteGroup
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Parent** | [**NestedSiteGroup**](NestedSiteGroup.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**SiteCount** | **Int32** |  | [readonly] 
**Depth** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$SiteGroup = Initialize-PSOpenAPIToolsSiteGroup  -Id null `
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
 -SiteCount null `
 -Depth null
```

- Convert the resource to JSON
```powershell
$SiteGroup | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

