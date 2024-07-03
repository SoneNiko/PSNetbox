# SavedFilter
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**ContentTypes** | **String[]** |  | 
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Description** | **String** |  | [optional] 
**User** | **Int32** |  | [optional] 
**Weight** | **Int32** |  | [optional] 
**Enabled** | **Boolean** |  | [optional] 
**Shared** | **Boolean** |  | [optional] 
**Parameters** | [**AnyType**](.md) |  | 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$SavedFilter = Initialize-PSOpenAPIToolsSavedFilter  -Id null `
 -Url null `
 -Display null `
 -ContentTypes null `
 -Name null `
 -Slug null `
 -Description null `
 -User null `
 -Weight null `
 -Enabled null `
 -Shared null `
 -Parameters null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$SavedFilter | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

