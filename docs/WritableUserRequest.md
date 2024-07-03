# WritableUserRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Username** | **String** | Required. 150 characters or fewer. Letters, digits and @/./+/-/_ only. | 
**Password** | **String** |  | 
**FirstName** | **String** |  | [optional] 
**LastName** | **String** |  | [optional] 
**Email** | **String** |  | [optional] 
**IsStaff** | **Boolean** | Designates whether the user can log into this admin site. | [optional] 
**IsActive** | **Boolean** | Designates whether this user should be treated as active. Unselect this instead of deleting accounts. | [optional] 
**DateJoined** | **System.DateTime** |  | [optional] 
**LastLogin** | **System.DateTime** |  | [optional] 
**Groups** | **Int32[]** | The groups this user belongs to. A user will get all permissions granted to each of their groups. | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableUserRequest = Initialize-PSOpenAPIToolsWritableUserRequest  -Username null `
 -Password null `
 -FirstName null `
 -LastName null `
 -Email null `
 -IsStaff null `
 -IsActive null `
 -DateJoined null `
 -LastLogin null `
 -Groups null
```

- Convert the resource to JSON
```powershell
$WritableUserRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

