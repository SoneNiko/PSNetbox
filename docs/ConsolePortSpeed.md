# ConsolePortSpeed
## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | **Int32** | * &#x60;1200&#x60; - 1200 bps * &#x60;2400&#x60; - 2400 bps * &#x60;4800&#x60; - 4800 bps * &#x60;9600&#x60; - 9600 bps * &#x60;19200&#x60; - 19.2 kbps * &#x60;38400&#x60; - 38.4 kbps * &#x60;57600&#x60; - 57.6 kbps * &#x60;115200&#x60; - 115.2 kbps | [optional] 
**Label** | **String** |  | [optional] 

## Examples

- Prepare the resource
```powershell
$ConsolePortSpeed = Initialize-PSOpenAPIToolsConsolePortSpeed  -Value null `
 -Label null
```

- Convert the resource to JSON
```powershell
$ConsolePortSpeed | ConvertTo-JSON
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

