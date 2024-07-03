# ContactAssignmentRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ContentType** | **String** |  | 
**ObjectId** | **Int64** |  | 
**Contact** | [**NestedContactRequest**](NestedContactRequest.md) |  | 
**Role** | [**NestedContactRoleRequest**](NestedContactRoleRequest.md) |  | [optional] 
**Priority** | **String** | * &#x60;primary&#x60; - Primary * &#x60;secondary&#x60; - Secondary * &#x60;tertiary&#x60; - Tertiary * &#x60;inactive&#x60; - Inactive | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$ContactAssignmentRequest = Initialize-PSOpenAPIToolsContactAssignmentRequest  -ContentType null `
 -ObjectId null `
 -Contact null `
 -Role null `
 -Priority null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$ContactAssignmentRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

