# PowerPanelRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Site** | [**NestedSiteRequest**](NestedSiteRequest.md) |  | 
**Location** | [**NestedLocationRequest**](NestedLocationRequest.md) |  | [optional] 
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PowerPanelRequest = Initialize-PSOpenAPIToolsPowerPanelRequest  -Site null `
 -Location null `
 -Name null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PowerPanelRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

