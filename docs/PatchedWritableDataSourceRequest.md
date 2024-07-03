# PatchedWritableDataSourceRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | [optional] 
**Type** | **String** |  | [optional] 
**SourceUrl** | **String** |  | [optional] 
**Enabled** | **Boolean** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Parameters** | [**AnyType**](.md) |  | [optional] 
**IgnoreRules** | **String** | Patterns (one per line) matching files to ignore when syncing | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableDataSourceRequest = Initialize-PSOpenAPIToolsPatchedWritableDataSourceRequest  -Name null `
 -Type null `
 -SourceUrl null `
 -Enabled null `
 -Description null `
 -Comments null `
 -Parameters null `
 -IgnoreRules null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableDataSourceRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

