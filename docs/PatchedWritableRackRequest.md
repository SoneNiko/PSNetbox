# PatchedWritableRackRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **String** |  | [optional] 
**FacilityId** | **String** |  | [optional] 
**Site** | **Int32** |  | [optional] 
**Location** | **Int32** |  | [optional] 
**Tenant** | **Int32** |  | [optional] 
**Status** | **String** | * &#x60;reserved&#x60; - Reserved * &#x60;available&#x60; - Available * &#x60;planned&#x60; - Planned * &#x60;active&#x60; - Active * &#x60;deprecated&#x60; - Deprecated | [optional] 
**Role** | **Int32** | Functional role | [optional] 
**Serial** | **String** |  | [optional] 
**AssetTag** | **String** | A unique tag used to identify this rack | [optional] 
**Type** | **String** | * &#x60;2-post-frame&#x60; - 2-post frame * &#x60;4-post-frame&#x60; - 4-post frame * &#x60;4-post-cabinet&#x60; - 4-post cabinet * &#x60;wall-frame&#x60; - Wall-mounted frame * &#x60;wall-frame-vertical&#x60; - Wall-mounted frame (vertical) * &#x60;wall-cabinet&#x60; - Wall-mounted cabinet * &#x60;wall-cabinet-vertical&#x60; - Wall-mounted cabinet (vertical) | [optional] 
**Width** | **Int32** | Rail-to-rail width  * &#x60;10&#x60; - 10 inches * &#x60;19&#x60; - 19 inches * &#x60;21&#x60; - 21 inches * &#x60;23&#x60; - 23 inches | [optional] 
**UHeight** | **Int32** | Height in rack units | [optional] 
**StartingUnit** | **Int32** | Starting unit for rack | [optional] 
**Weight** | **Double** |  | [optional] 
**MaxWeight** | **Int32** | Maximum load capacity for the rack | [optional] 
**WeightUnit** | **String** | * &#x60;kg&#x60; - Kilograms * &#x60;g&#x60; - Grams * &#x60;lb&#x60; - Pounds * &#x60;oz&#x60; - Ounces | [optional] 
**DescUnits** | **Boolean** | Units are numbered top-to-bottom | [optional] 
**OuterWidth** | **Int32** | Outer dimension of rack (width) | [optional] 
**OuterDepth** | **Int32** | Outer dimension of rack (depth) | [optional] 
**OuterUnit** | **String** | * &#x60;mm&#x60; - Millimeters * &#x60;in&#x60; - Inches | [optional] 
**MountingDepth** | **Int32** | Maximum depth of a mounted device, in millimeters. For four-post racks, this is the distance between the front and rear rails. | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTagRequest[]**](NestedTagRequest.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritableRackRequest = Initialize-PSOpenAPIToolsPatchedWritableRackRequest  -Name null `
 -FacilityId null `
 -Site null `
 -Location null `
 -Tenant null `
 -Status null `
 -Role null `
 -Serial null `
 -AssetTag null `
 -Type null `
 -Width null `
 -UHeight null `
 -StartingUnit null `
 -Weight null `
 -MaxWeight null `
 -WeightUnit null `
 -DescUnits null `
 -OuterWidth null `
 -OuterDepth null `
 -OuterUnit null `
 -MountingDepth null `
 -Description null `
 -Comments null `
 -Tags null `
 -CustomFields null
```

- Convert the resource to JSON
```powershell
$PatchedWritableRackRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

