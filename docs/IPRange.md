# IPRange
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Family** | [**AggregateFamily**](AggregateFamily.md) |  | 
**StartAddress** | **String** |  | 
**EndAddress** | **String** |  | 
**Size** | **Int32** |  | [readonly] 
**Vrf** | [**NestedVRF**](NestedVRF.md) |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Status** | [**IPRangeStatus**](IPRangeStatus.md) |  | [optional] 
**Role** | [**NestedRole**](NestedRole.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**MarkUtilized** | **Boolean** | Treat as fully utilized | [optional] 

## Examples

- Prepare the resource
```powershell
$IPRange = Initialize-PSOpenAPIToolsIPRange  -Id null `
 -Url null `
 -Display null `
 -Family null `
 -StartAddress null `
 -EndAddress null `
 -Size null `
 -Vrf null `
 -Tenant null `
 -Status null `
 -Role null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -MarkUtilized null
```

- Convert the resource to JSON
```powershell
$IPRange | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

