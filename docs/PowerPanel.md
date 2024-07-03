# PowerPanel
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Site** | [**NestedSite**](NestedSite.md) |  | 
**Location** | [**NestedLocation**](NestedLocation.md) |  | [optional] 
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**PowerfeedCount** | **Int32** |  | [readonly] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$PowerPanel = Initialize-PSOpenAPIToolsPowerPanel  -Id null `
 -Url null `
 -Display null `
 -Site null `
 -Location null `
 -Name null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -PowerfeedCount null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$PowerPanel | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

