# WritableVMInterfaceRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**VirtualMachine** | **Int32** |  | 
**Name** | **String** |  | 
**Enabled** | **Boolean** |  | [optional] 
**Parent** | **Int32** |  | [optional] 
**Bridge** | **Int32** |  | [optional] 
**Mtu** | **Int32** |  | [optional] 
**MacAddress** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**Mode** | **String** | IEEE 802.1Q tagging strategy  * &#x60;access&#x60; - Access * &#x60;tagged&#x60; - Tagged * &#x60;tagged-all&#x60; - Tagged (All) | [optional] 
**UntaggedVlan** | **Int32** |  | [optional] 
**TaggedVlans** | **Int32[]** |  | [optional] 
**Vrf** | **Int32** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$WritableVMInterfaceRequest = Initialize-PSOpenAPIToolsWritableVMInterfaceRequest  -VirtualMachine null `
 -Name null `
 -Enabled null `
 -Parent null `
 -Bridge null `
 -Mtu null `
 -MacAddress null `
 -Description null `
 -Mode null `
 -UntaggedVlan null `
 -TaggedVlans null `
 -Vrf null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$WritableVMInterfaceRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

