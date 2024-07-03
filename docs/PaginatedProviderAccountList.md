# PaginatedProviderAccountList
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Count** | **Int32** |  | [optional] 
**Next** | **String** |  | [optional] 
**Previous** | **String** |  | [optional] 
**Results** | [**ProviderAccount[]**](ProviderAccount.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PaginatedProviderAccountList = Initialize-PSOpenAPIToolsPaginatedProviderAccountList  -Count 123 `
 -Next http://api.example.org/accounts/?offset&#x3D;400&amp;limit&#x3D;100 `
 -Previous http://api.example.org/accounts/?offset&#x3D;200&amp;limit&#x3D;100 `
 -Results null
```

- Convert the resource to JSON
```powershell
$PaginatedProviderAccountList | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

