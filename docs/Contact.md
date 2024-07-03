# Contact
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Group** | [**NestedContactGroup**](NestedContactGroup.md) |  | [optional] 
**Name** | **String** |  | 
**Title** | **String** |  | [optional] 
**Phone** | **String** |  | [optional] 
**Email** | **String** |  | [optional] 
**Address** | **String** |  | [optional] 
**Link** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Contact = Initialize-PSOpenAPIToolsContact  -Id null `
 -Url null `
 -Display null `
 -Group null `
 -Name null `
 -Title null `
 -Phone null `
 -Email null `
 -Address null `
 -Link null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$Contact | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

