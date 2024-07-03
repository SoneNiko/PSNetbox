# Provider
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** | Full name of the provider | 
**Slug** | **String** |  | 
**Accounts** | **Int32[]** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Asns** | **Int32[]** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**CircuitCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Provider = Initialize-PSOpenAPIToolsProvider  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Slug null `
 -Accounts null `
 -Description null `
 -Comments null `
 -Asns null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -CircuitCount null
```

- Convert the resource to JSON
```powershell
$Provider | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

