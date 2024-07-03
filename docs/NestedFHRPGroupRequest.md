# NestedFHRPGroupRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Protocol** | **String** | * &#x60;vrrp2&#x60; - VRRPv2 * &#x60;vrrp3&#x60; - VRRPv3 * &#x60;carp&#x60; - CARP * &#x60;clusterxl&#x60; - ClusterXL * &#x60;hsrp&#x60; - HSRP * &#x60;glbp&#x60; - GLBP * &#x60;other&#x60; - Other | 
**GroupId** | **Int32** |  | 

## Examples

- Prepare the resource
```powershell
$NestedFHRPGroupRequest = Initialize-PSOpenAPIToolsNestedFHRPGroupRequest  -Protocol null `
 -GroupId null
```

- Convert the resource to JSON
```powershell
$NestedFHRPGroupRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

