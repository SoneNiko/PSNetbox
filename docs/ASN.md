# ASN
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Asn** | **Int64** | 16- or 32-bit autonomous system number | 
**Rir** | [**NestedRIR**](NestedRIR.md) |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**SiteCount** | **Int32** |  | [readonly] 
**ProviderCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$ASN = Initialize-PSOpenAPIToolsASN  -Id null `
 -Url null `
 -Display null `
 -Asn null `
 -Rir null `
 -Tenant null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -SiteCount null `
 -ProviderCount null
```

- Convert the resource to JSON
```powershell
$ASN | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

