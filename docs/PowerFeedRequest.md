# PowerFeedRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PowerPanel** | [**NestedPowerPanelRequest**](NestedPowerPanelRequest.md) |  | 
**Rack** | [**NestedRackRequest**](NestedRackRequest.md) |  | [optional] 
**Name** | **String** |  | 
**Status** | **String** | * &#x60;offline&#x60; - Offline * &#x60;active&#x60; - Active * &#x60;planned&#x60; - Planned * &#x60;failed&#x60; - Failed | [optional] 
**Type** | **String** | * &#x60;primary&#x60; - Primary * &#x60;redundant&#x60; - Redundant | [optional] 
**Supply** | **String** | * &#x60;ac&#x60; - AC * &#x60;dc&#x60; - DC | [optional] 
**Phase** | **String** | * &#x60;single-phase&#x60; - Single phase * &#x60;three-phase&#x60; - Three-phase | [optional] 
**Voltage** | **Int32** |  | [optional] 
**Amperage** | **Int32** |  | [optional] 
**MaxUtilization** | **Int32** | Maximum permissible draw (percentage) | [optional] 
**MarkConnected** | **Boolean** | Treat as if a cable is connected | [optional] 
**Description** | **String** |  | [optional] 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PowerFeedRequest = Initialize-PSOpenAPIToolsPowerFeedRequest  -PowerPanel null `
 -Rack null `
 -Name null `
 -Status null `
 -Type null `
 -Supply null `
 -Phase null `
 -Voltage null `
 -Amperage null `
 -MaxUtilization null `
 -MarkConnected null `
 -Description null `
 -Tenant null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PowerFeedRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

