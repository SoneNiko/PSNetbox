# FHRPGroup
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Name** | **String** |  | [optional] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Protocol** | **String** | * &#x60;vrrp2&#x60; - VRRPv2 * &#x60;vrrp3&#x60; - VRRPv3 * &#x60;carp&#x60; - CARP * &#x60;clusterxl&#x60; - ClusterXL * &#x60;hsrp&#x60; - HSRP * &#x60;glbp&#x60; - GLBP * &#x60;other&#x60; - Other | 
**GroupId** | **Int32** |  | 
**AuthType** | **String** | * &#x60;plaintext&#x60; - Plaintext * &#x60;md5&#x60; - MD5 | [optional] 
**AuthKey** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**IpAddresses** | [**NestedIPAddress[]**](NestedIPAddress.md) |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$FHRPGroup = Initialize-PSOpenAPIToolsFHRPGroup  -Id null `
 -Name null `
 -Url null `
 -Display null `
 -Protocol null `
 -GroupId null `
 -AuthType null `
 -AuthKey null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -IpAddresses null
```

- Convert the resource to JSON
```powershell
$FHRPGroup | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

