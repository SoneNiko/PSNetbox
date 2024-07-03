# ModuleBay
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Device** | [**NestedDevice**](NestedDevice.md) |  | 
**Name** | **String** |  | 
**InstalledModule** | [**ModuleBayNestedModule**](ModuleBayNestedModule.md) |  | [optional] 
**Label** | **String** | Physical label | [optional] 
**Position** | **String** | Identifier to reference when renaming installed components | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$ModuleBay = Initialize-PSOpenAPIToolsModuleBay  -Id null `
 -Url null `
 -Display null `
 -Device null `
 -Name null `
 -InstalledModule null `
 -Label null `
 -Position null `
 -Description null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$ModuleBay | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

