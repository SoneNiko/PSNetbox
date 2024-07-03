# PatchedWritablePowerOutletTemplateRequest
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DeviceType** | **Int32** |  | [optional] 
**ModuleType** | **Int32** |  | [optional] 
**Name** | **String** | {module} is accepted as a substitution for the module bay position when attached to a module type. | [optional] 
**Label** | **String** | Physical label | [optional] 
**Type** | **String** | * &#x60;iec-60320-c5&#x60; - C5 * &#x60;iec-60320-c7&#x60; - C7 * &#x60;iec-60320-c13&#x60; - C13 * &#x60;iec-60320-c15&#x60; - C15 * &#x60;iec-60320-c19&#x60; - C19 * &#x60;iec-60320-c21&#x60; - C21 * &#x60;iec-60309-p-n-e-4h&#x60; - P+N+E 4H * &#x60;iec-60309-p-n-e-6h&#x60; - P+N+E 6H * &#x60;iec-60309-p-n-e-9h&#x60; - P+N+E 9H * &#x60;iec-60309-2p-e-4h&#x60; - 2P+E 4H * &#x60;iec-60309-2p-e-6h&#x60; - 2P+E 6H * &#x60;iec-60309-2p-e-9h&#x60; - 2P+E 9H * &#x60;iec-60309-3p-e-4h&#x60; - 3P+E 4H * &#x60;iec-60309-3p-e-6h&#x60; - 3P+E 6H * &#x60;iec-60309-3p-e-9h&#x60; - 3P+E 9H * &#x60;iec-60309-3p-n-e-4h&#x60; - 3P+N+E 4H * &#x60;iec-60309-3p-n-e-6h&#x60; - 3P+N+E 6H * &#x60;iec-60309-3p-n-e-9h&#x60; - 3P+N+E 9H * &#x60;iec-60906-1&#x60; - IEC 60906-1 * &#x60;nbr-14136-10a&#x60; - 2P+T 10A (NBR 14136) * &#x60;nbr-14136-20a&#x60; - 2P+T 20A (NBR 14136) * &#x60;nema-1-15r&#x60; - NEMA 1-15R * &#x60;nema-5-15r&#x60; - NEMA 5-15R * &#x60;nema-5-20r&#x60; - NEMA 5-20R * &#x60;nema-5-30r&#x60; - NEMA 5-30R * &#x60;nema-5-50r&#x60; - NEMA 5-50R * &#x60;nema-6-15r&#x60; - NEMA 6-15R * &#x60;nema-6-20r&#x60; - NEMA 6-20R * &#x60;nema-6-30r&#x60; - NEMA 6-30R * &#x60;nema-6-50r&#x60; - NEMA 6-50R * &#x60;nema-10-30r&#x60; - NEMA 10-30R * &#x60;nema-10-50r&#x60; - NEMA 10-50R * &#x60;nema-14-20r&#x60; - NEMA 14-20R * &#x60;nema-14-30r&#x60; - NEMA 14-30R * &#x60;nema-14-50r&#x60; - NEMA 14-50R * &#x60;nema-14-60r&#x60; - NEMA 14-60R * &#x60;nema-15-15r&#x60; - NEMA 15-15R * &#x60;nema-15-20r&#x60; - NEMA 15-20R * &#x60;nema-15-30r&#x60; - NEMA 15-30R * &#x60;nema-15-50r&#x60; - NEMA 15-50R * &#x60;nema-15-60r&#x60; - NEMA 15-60R * &#x60;nema-l1-15r&#x60; - NEMA L1-15R * &#x60;nema-l5-15r&#x60; - NEMA L5-15R * &#x60;nema-l5-20r&#x60; - NEMA L5-20R * &#x60;nema-l5-30r&#x60; - NEMA L5-30R * &#x60;nema-l5-50r&#x60; - NEMA L5-50R * &#x60;nema-l6-15r&#x60; - NEMA L6-15R * &#x60;nema-l6-20r&#x60; - NEMA L6-20R * &#x60;nema-l6-30r&#x60; - NEMA L6-30R * &#x60;nema-l6-50r&#x60; - NEMA L6-50R * &#x60;nema-l10-30r&#x60; - NEMA L10-30R * &#x60;nema-l14-20r&#x60; - NEMA L14-20R * &#x60;nema-l14-30r&#x60; - NEMA L14-30R * &#x60;nema-l14-50r&#x60; - NEMA L14-50R * &#x60;nema-l14-60r&#x60; - NEMA L14-60R * &#x60;nema-l15-20r&#x60; - NEMA L15-20R * &#x60;nema-l15-30r&#x60; - NEMA L15-30R * &#x60;nema-l15-50r&#x60; - NEMA L15-50R * &#x60;nema-l15-60r&#x60; - NEMA L15-60R * &#x60;nema-l21-20r&#x60; - NEMA L21-20R * &#x60;nema-l21-30r&#x60; - NEMA L21-30R * &#x60;nema-l22-30r&#x60; - NEMA L22-30R * &#x60;CS6360C&#x60; - CS6360C * &#x60;CS6364C&#x60; - CS6364C * &#x60;CS8164C&#x60; - CS8164C * &#x60;CS8264C&#x60; - CS8264C * &#x60;CS8364C&#x60; - CS8364C * &#x60;CS8464C&#x60; - CS8464C * &#x60;ita-e&#x60; - ITA Type E (CEE 7/5) * &#x60;ita-f&#x60; - ITA Type F (CEE 7/3) * &#x60;ita-g&#x60; - ITA Type G (BS 1363) * &#x60;ita-h&#x60; - ITA Type H * &#x60;ita-i&#x60; - ITA Type I * &#x60;ita-j&#x60; - ITA Type J * &#x60;ita-k&#x60; - ITA Type K * &#x60;ita-l&#x60; - ITA Type L (CEI 23-50) * &#x60;ita-m&#x60; - ITA Type M (BS 546) * &#x60;ita-n&#x60; - ITA Type N * &#x60;ita-o&#x60; - ITA Type O * &#x60;ita-multistandard&#x60; - ITA Multistandard * &#x60;usb-a&#x60; - USB Type A * &#x60;usb-micro-b&#x60; - USB Micro B * &#x60;usb-c&#x60; - USB Type C * &#x60;dc-terminal&#x60; - DC Terminal * &#x60;hdot-cx&#x60; - HDOT Cx * &#x60;saf-d-grid&#x60; - Saf-D-Grid * &#x60;neutrik-powercon-20a&#x60; - Neutrik powerCON (20A) * &#x60;neutrik-powercon-32a&#x60; - Neutrik powerCON (32A) * &#x60;neutrik-powercon-true1&#x60; - Neutrik powerCON TRUE1 * &#x60;neutrik-powercon-true1-top&#x60; - Neutrik powerCON TRUE1 TOP * &#x60;ubiquiti-smartpower&#x60; - Ubiquiti SmartPower * &#x60;hardwired&#x60; - Hardwired * &#x60;other&#x60; - Other | [optional] 
**PowerPort** | **Int32** |  | [optional] 
**FeedLeg** | **String** | Phase (for three-phase feeds)  * &#x60;A&#x60; - A * &#x60;B&#x60; - B * &#x60;C&#x60; - C | [optional] 
**Description** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$PatchedWritablePowerOutletTemplateRequest = Initialize-PSOpenAPIToolsPatchedWritablePowerOutletTemplateRequest  -DeviceType null `
 -ModuleType null `
 -Name null `
 -Label null `
 -Type null `
 -PowerPort null `
 -FeedLeg null `
 -Description null
```

- Convert the resource to JSON
```powershell
$PatchedWritablePowerOutletTemplateRequest | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

