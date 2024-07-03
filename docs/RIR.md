# RIR
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**IsPrivate** | **Boolean** | IP space managed by this RIR is considered private | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**AggregateCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$RIR = Initialize-PSOpenAPIToolsRIR  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null `
 -IsPrivate null `
 -Description null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -AggregateCount null
```

- Convert the resource to JSON
```powershell
$RIR | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

