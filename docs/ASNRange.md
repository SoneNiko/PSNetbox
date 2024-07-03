# ASNRange
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Rir** | [**NestedRIR**](NestedRIR.md) |  | 
**Start** | **Int64** |  | 
**VarEnd** | **Int64** |  | 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**AsnCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$ASNRange = Initialize-PSOpenAPIToolsASNRange  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null `
 -Rir null `
 -Start null `
 -VarEnd null `
 -Tenant null `
 -Description null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -AsnCount null
```

- Convert the resource to JSON
```powershell
$ASNRange | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

