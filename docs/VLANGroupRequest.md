# VLANGroupRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Slug** | **String** |  | 
**ScopeType** | **String** |  | [optional] 
**ScopeId** | **Int32** |  | [optional] 
**MinVid** | **Int32** | Lowest permissible ID of a child VLAN | [optional] 
**MaxVid** | **Int32** | Highest permissible ID of a child VLAN | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$VLANGroupRequest = Initialize-PSOpenAPIToolsVLANGroupRequest  -Name null `
 -Slug null `
 -ScopeType null `
 -ScopeId null `
 -MinVid null `
 -MaxVid null `
 -Description null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$VLANGroupRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

