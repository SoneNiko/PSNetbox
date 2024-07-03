# ObjectPermission
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
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
$ObjectPermission = Initialize-PSOpenAPIToolsObjectPermission  -Id null `
 -Url null `
 -Display null `
 -Name null `
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
$ObjectPermission | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

