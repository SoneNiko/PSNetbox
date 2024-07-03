# Cable
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Type** | **String** | * &#x60;cat3&#x60; - CAT3 * &#x60;cat5&#x60; - CAT5 * &#x60;cat5e&#x60; - CAT5e * &#x60;cat6&#x60; - CAT6 * &#x60;cat6a&#x60; - CAT6a * &#x60;cat7&#x60; - CAT7 * &#x60;cat7a&#x60; - CAT7a * &#x60;cat8&#x60; - CAT8 * &#x60;dac-active&#x60; - Direct Attach Copper (Active) * &#x60;dac-passive&#x60; - Direct Attach Copper (Passive) * &#x60;mrj21-trunk&#x60; - MRJ21 Trunk * &#x60;coaxial&#x60; - Coaxial * &#x60;mmf&#x60; - Multimode Fiber * &#x60;mmf-om1&#x60; - Multimode Fiber (OM1) * &#x60;mmf-om2&#x60; - Multimode Fiber (OM2) * &#x60;mmf-om3&#x60; - Multimode Fiber (OM3) * &#x60;mmf-om4&#x60; - Multimode Fiber (OM4) * &#x60;mmf-om5&#x60; - Multimode Fiber (OM5) * &#x60;smf&#x60; - Singlemode Fiber * &#x60;smf-os1&#x60; - Singlemode Fiber (OS1) * &#x60;smf-os2&#x60; - Singlemode Fiber (OS2) * &#x60;aoc&#x60; - Active Optical Cabling (AOC) * &#x60;power&#x60; - Power | [optional] 
**ATerminations** | [**GenericObject[]**](GenericObject.md) |  | [optional] 
**BTerminations** | [**GenericObject[]**](GenericObject.md) |  | [optional] 
**Status** | [**CableStatus**](CableStatus.md) |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Label** | **String** |  | [optional] 
**Color** | **String** |  | [optional] 
**Length** | **Double** |  | [optional] 
**LengthUnit** | [**CableLengthUnit**](CableLengthUnit.md) |  | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Cable = Initialize-PSOpenAPIToolsCable  -Id null `
 -Url null `
 -Display null `
 -Type null `
 -ATerminations null `
 -BTerminations null `
 -Status null `
 -Tenant null `
 -Label null `
 -Color null `
 -Length null `
 -LengthUnit null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null `
 -Created null `
 -LastUpdated null
```

- Convert the resource to JSON
```powershell
$Cable | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

