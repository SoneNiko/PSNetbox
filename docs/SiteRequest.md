# SiteRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** | Full name of the site | 
**Slug** | **String** |  | 
**Status** | **String** | * &#x60;planned&#x60; - Planned * &#x60;staging&#x60; - Staging * &#x60;active&#x60; - Active * &#x60;decommissioning&#x60; - Decommissioning * &#x60;retired&#x60; - Retired | [optional] 
**Region** | [**NestedRegionRequest**](NestedRegionRequest.md) |  | [optional] 
**Group** | [**NestedSiteGroupRequest**](NestedSiteGroupRequest.md) |  | [optional] 
**Tenant** | [**NestedTenantRequest**](NestedTenantRequest.md) |  | [optional] 
**Facility** | **String** | Local facility ID or description | [optional] 
**TimeZone** | **String** |  | [optional] 
**Description** | **String** |  | [optional] 
**PhysicalAddress** | **String** | Physical location of the building | [optional] 
**ShippingAddress** | **String** | If different from the physical address | [optional] 
**Latitude** | **Double** | GPS coordinate in decimal format (xx.yyyyyy) | [optional] 
**Longitude** | **Double** | GPS coordinate in decimal format (xx.yyyyyy) | [optional] 
**Comments** | **String** |  | [optional] 
**Asns** | **Int32[]** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$SiteRequest = Initialize-PSOpenAPIToolsSiteRequest  -Name null `
 -Slug null `
 -Status null `
 -Region null `
 -Group null `
 -Tenant null `
 -Facility null `
 -TimeZone null `
 -Description null `
 -PhysicalAddress null `
 -ShippingAddress null `
 -Latitude null `
 -Longitude null `
 -Comments null `
 -Asns null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$SiteRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

