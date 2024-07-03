# Aggregate
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Family** | [**AggregateFamily**](AggregateFamily.md) |  | 
**Prefix** | **String** |  | 
**Rir** | [**NestedRIR**](NestedRIR.md) |  | 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**DateAdded** | **System.DateTime** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Aggregate = Initialize-PSOpenAPIToolsAggregate  -Id null `
 -Url null `
 -Display null `
 -Family null `
 -Prefix null `
 -Rir null `
 -Tenant null `
 -DateAdded null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$Aggregate | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

