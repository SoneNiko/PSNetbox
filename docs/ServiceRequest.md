# ServiceRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Device** | [**NestedDeviceRequest**](NestedDeviceRequest.md) |  | [optional] 
**VirtualMachine** | [**NestedVirtualMachineRequest**](NestedVirtualMachineRequest.md) |  | [optional] 
**Name** | **String** |  | 
**Ports** | **Int32[]** |  | 
**Protocol** | **String** | * &#x60;tcp&#x60; - TCP * &#x60;udp&#x60; - UDP * &#x60;sctp&#x60; - SCTP | [optional] 
**Ipaddresses** | **Int32[]** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$ServiceRequest = Initialize-PSOpenAPIToolsServiceRequest  -Device null `
 -VirtualMachine null `
 -Name null `
 -Ports null `
 -Protocol null `
 -Ipaddresses null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$ServiceRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

