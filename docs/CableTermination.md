# CableTermination
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Cable** | **Int32** |  | 
**CableEnd** | **String** | * &#x60;A&#x60; - A * &#x60;B&#x60; - B | 
**TerminationType** | **String** |  | 
**TerminationId** | **Int64** |  | 
**Termination** | [**AnyType**](.md) |  | [readonly] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$CableTermination = Initialize-PSOpenAPIToolsCableTermination  -Id null `
 -Url null `
 -Display null `
 -Cable null `
 -CableEnd null `
 -TerminationType null `
 -TerminationId null `
 -Termination null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$CableTermination | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

