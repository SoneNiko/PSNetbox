# VRFRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Rd** | **String** | Unique route distinguisher (as defined in RFC 4364) | [optional] 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**EnforceUnique** | **Boolean** | Prevent duplicate prefixes/IP addresses within this VRF | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**ImportTargets** | **Int32[]** |  | [optional] 
**ExportTargets** | **Int32[]** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$VRFRequest = Initialize-PSOpenAPIToolsVRFRequest  -Name null `
 -Rd null `
 -Tenant null `
 -EnforceUnique null `
 -Description null `
 -Comments null `
 -ImportTargets null `
 -ExportTargets null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$VRFRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

