# TokenProvision
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**User** | [**NestedUser**](NestedUser.md) |  | [readonly] 
**Created** | **System.DateTime** |  | [readonly] 
**Expires** | **System.DateTime** |  | [optional] 
**LastUsed** | **System.DateTime** |  | [readonly] 
**Key** | **String** |  | [readonly] 
**WriteEnabled** | **Boolean** | Permit create/update/delete operations using this key | [optional] 
**Description** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$TokenProvision = Initialize-PSOpenAPIToolsTokenProvision  -Id null `
 -Url null `
 -Display null `
 -User null `
 -Created null `
 -Expires null `
 -LastUsed null `
 -Key null `
 -WriteEnabled null `
 -Description null
```

- Convert the resource to JSON
```powershell
$TokenProvision | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

