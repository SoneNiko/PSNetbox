# GenericObject
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ObjectType** | **String** |  | 
**ObjectId** | **Int32** |  | 
**Object** | [**AnyType**](.md) |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$GenericObject = Initialize-PSOpenAPIToolsGenericObject  -ObjectType null `
 -ObjectId null `
 -Object null
```

- Convert the resource to JSON
```powershell
$GenericObject | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

