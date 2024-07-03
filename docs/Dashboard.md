# Dashboard
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Layout** | [**AnyType**](.md) |  | [optional] 
**Config** | [**AnyType**](.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$Dashboard = Initialize-PSOpenAPIToolsDashboard  -Layout null `
 -Config null
```

- Convert the resource to JSON
```powershell
$Dashboard | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

