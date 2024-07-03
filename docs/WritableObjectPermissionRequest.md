# WritableObjectPermissionRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | 
**Description** | **String** |  | [optional] 
**Enabled** | **Boolean** |  | [optional] 
**ObjectTypes** | **String[]** |  | 
**Groups** | **Int32[]** |  | [optional] 
**Users** | **Int32[]** |  | [optional] 
**Actions** | **String[]** | The list of actions granted by this permission | 
**Constraints** | [**AnyType**](.md) | Queryset filter matching the applicable objects of the selected type(s) | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableObjectPermissionRequest = Initialize-PSOpenAPIToolsWritableObjectPermissionRequest  -Name null `
 -Description null `
 -Enabled null `
 -ObjectTypes null `
 -Groups null `
 -Users null `
 -Actions null `
 -Constraints null
```

- Convert the resource to JSON
```powershell
$WritableObjectPermissionRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

