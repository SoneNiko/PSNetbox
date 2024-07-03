# User
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Username** | **String** | Required. 150 characters or fewer. Letters, digits and @/./+/-/_ only. | 
**FirstName** | **String** |  | [optional] 
**LastName** | **String** |  | [optional] 
**Email** | **String** |  | [optional] 
**IsStaff** | **Boolean** | Designates whether the user can log into this admin site. | [optional] 
**IsActive** | **Boolean** | Designates whether this user should be treated as active. Unselect this instead of deleting accounts. | [optional] 
**DateJoined** | **System.DateTime** |  | [optional] 
**LastLogin** | **System.DateTime** |  | [optional] 
**Groups** | **Int32[]** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$User = Initialize-PSOpenAPIToolsUser  -Id null `
 -Url null `
 -Display null `
 -Username null `
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
$User | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

