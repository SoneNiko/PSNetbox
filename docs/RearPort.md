# RearPort
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Device** | [**NestedDevice**](NestedDevice.md) |  | 
**Module** | [**ComponentNestedModule**](ComponentNestedModule.md) |  | [optional] 
**Name** | **String** |  | 
**Label** | **String** | Physical label | [optional] 
**Type** | [**FrontPortType**](FrontPortType.md) |  | 
**Color** | **String** |  | [optional] 
**Positions** | **Int32** | Number of front ports which may be mapped | [optional] 
**Description** | **String** |  | [optional] 
**MarkConnected** | **Boolean** | Treat as if a cable is connected | [optional] 
**Cable** | [**NestedCable**](NestedCable.md) |  | [readonly] 
**CableEnd** | **String** |  | [readonly] 
**LinkPeers** | [**AnyType[]**](AnyType.md) |  | [readonly] 
**LinkPeersType** | **String** | Return the type of the peer link terminations, or None. | [readonly] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**Occupied** | **Boolean** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$RearPort = Initialize-PSOpenAPIToolsRearPort  -Id null `
 -Url null `
 -Display null `
 -Device null `
 -Module null `
 -Name null `
 -Label null `
 -Type null `
 -Color null `
 -Positions null `
 -Description null `
 -MarkConnected null `
 -Cable null `
 -CableEnd null `
 -LinkPeers null `
 -LinkPeersType null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -Occupied null
```

- Convert the resource to JSON
```powershell
$RearPort | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

