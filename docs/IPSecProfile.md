# IPSecProfile
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**Mode** | [**IPSecProfileMode**](IPSecProfileMode.md) |  | 
**IkePolicy** | [**NestedIKEPolicy**](NestedIKEPolicy.md) |  | 
**IpsecPolicy** | [**NestedIPSecPolicy**](NestedIPSecPolicy.md) |  | 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$IPSecProfile = Initialize-PSOpenAPIToolsIPSecProfile  -Id null `
 -Url null `
 -Display null `
 -Name null `
 -Description null `
 -Mode null `
 -IkePolicy null `
 -IpsecPolicy null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$IPSecProfile | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

