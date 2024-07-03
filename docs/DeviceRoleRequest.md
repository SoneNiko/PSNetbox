# DeviceRoleRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Slug** | **String** |  | 
**Color** | **String** |  | [optional] 
**VmRole** | **Boolean** | Virtual machines may be assigned to this role | [optional] 
**ConfigTemplate** | [**NestedConfigTemplateRequest**](NestedConfigTemplateRequest.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$DeviceRoleRequest = Initialize-PSOpenAPIToolsDeviceRoleRequest  -Name null `
 -Slug null `
 -Color null `
 -VmRole null `
 -ConfigTemplate null `
 -Description null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$DeviceRoleRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

