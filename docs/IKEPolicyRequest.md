# IKEPolicyRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**Version** | **Int32** | * &#x60;1&#x60; - IKEv1 * &#x60;2&#x60; - IKEv2 | 
**Mode** | **String** | * &#x60;aggressive&#x60; - Aggressive * &#x60;main&#x60; - Main | 
**Proposals** | **Int32[]** |  | [optional] 
**PresharedKey** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$IKEPolicyRequest = Initialize-PSOpenAPIToolsIKEPolicyRequest  -Name null `
 -Description null `
 -Version null `
 -Mode null `
 -Proposals null `
 -PresharedKey null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$IKEPolicyRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

