# StatusBar JSONPath

Shows the path to the selected JSON Property in the StatusBar.

![JSONPath](resources/jsonpath.png)

## Updates:

- 1.4.5: Extended filtypes (Amazon State Language (asl), AWS System Manager Document (ssm-json))
- Only shows Path for JSON files (and 'JSON with comments', although this may cause path detection issues).
- StatusBar item now copies to Clipboard - thanks to Tyderion.
- Switched clipboard package - thanks to floatdrop
- Fixed issue with slashes preceeding quotes
- Fixed issue with file detection - thanks to Outrigger047
- Support for more special characters - thanks to Nuaduwodan

## Known Issues

- Only works for registered (JSON) files.
