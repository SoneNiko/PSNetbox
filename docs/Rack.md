# Rack
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **Int32** |  | [readonly] 
**Url** | **String** |  | [readonly] 
**Display** | **String** |  | [readonly] 
**Name** | **String** |  | 
**FacilityId** | **String** |  | [optional] 
**Site** | [**NestedSite**](NestedSite.md) |  | 
**Location** | [**NestedLocation**](NestedLocation.md) |  | [optional] 
**Tenant** | [**NestedTenant**](NestedTenant.md) |  | [optional] 
**Status** | [**RackStatus**](RackStatus.md) |  | [optional] 
**Role** | [**NestedRackRole**](NestedRackRole.md) |  | [optional] 
**Serial** | **String** |  | [optional] 
**AssetTag** | **String** | A unique tag used to identify this rack | [optional] 
**Type** | [**RackType**](RackType.md) |  | [optional] 
**Width** | [**RackWidth**](RackWidth.md) |  | [optional] 
**UHeight** | **Int32** | Height in rack units | [optional] 
**StartingUnit** | **Int32** | Starting unit for rack | [optional] 
**Weight** | **Double** |  | [optional] 
**MaxWeight** | **Int32** | Maximum load capacity for the rack | [optional] 
**WeightUnit** | [**DeviceTypeWeightUnit**](DeviceTypeWeightUnit.md) |  | [optional] 
**DescUnits** | **Boolean** | Units are numbered top-to-bottom | [optional] 
**OuterWidth** | **Int32** | Outer dimension of rack (width) | [optional] 
**OuterDepth** | **Int32** | Outer dimension of rack (depth) | [optional] 
**OuterUnit** | [**RackOuterUnit**](RackOuterUnit.md) |  | [optional] 
**MountingDepth** | **Int32** | Maximum depth of a mounted device, in millimeters. For four-post racks, this is the distance between the front and rear rails. | [optional] 
**Description** | **String** |  | [optional] 
**Comments** | **String** |  | [optional] 
**Tags** | [**NestedTag[]**](NestedTag.md) |  | [optional] 
**CustomFields** | [**System.Collections.Hashtable**](AnyType.md) |  | [optional] 
**Created** | **System.DateTime** |  | [readonly] 
**LastUpdated** | **System.DateTime** |  | [readonly] 
**DeviceCount** | **Int32** |  | [readonly] 
**PowerfeedCount** | **Int32** |  | [readonly] 

## Examples

- Prepare the resource
```powershell
$Rack = Initialize-PSOpenAPIToolsRack  -Id null `
 -Url null `
 -Display null `
 -Name null `
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
 -CustomFields null `
 -Created null `
 -LastUpdated null `
 -DeviceCount null `
 -PowerfeedCount null
```

- Convert the resource to JSON
```powershell
$Rack | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

