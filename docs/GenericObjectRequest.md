# GenericObjectRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ObjectType** | **String** |  | 
**ObjectId** | **Int32** |  | 

## Examples

- Prepare the resource
```powershell
$GenericObjectRequest = Initialize-PSOpenAPIToolsGenericObjectRequest  -ObjectType null `
 -ObjectId null
```

- Convert the resource to JSON
```powershell
$GenericObjectRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

