# VMInterfaceRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**VirtualMachine** | [**NestedVirtualMachineRequest**](NestedVirtualMachineRequest.md) |  | 
**Name** | **String** |  | 
**Enabled** | **Boolean** |  | [optional] 
**Parent** | [**NestedVMInterfaceRequest**](NestedVMInterfaceRequest.md) |  | [optional] 
**Bridge** | [**NestedVMInterfaceRequest**](NestedVMInterfaceRequest.md) |  | [optional] 
**Mtu** | **Int32** |  | [optional] 
**MacAddress** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**Mode** | **String** | * &#x60;access&#x60; - Access * &#x60;tagged&#x60; - Tagged * &#x60;tagged-all&#x60; - Tagged (All) | [optional] 
**UntaggedVlan** | [**NestedVLANRequest**](NestedVLANRequest.md) |  | [optional] 
**TaggedVlans** | **Int32[]** |  | [optional] 
**Vrf** | [**NestedVRFRequest**](NestedVRFRequest.md) |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$VMInterfaceRequest = Initialize-PSOpenAPIToolsVMInterfaceRequest  -VirtualMachine null `
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
$VMInterfaceRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

