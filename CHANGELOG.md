## Changelog

### v2.1.1 (2026-02-06)
- Added custom username field in settings
- Fixed username detection using `sdk.State.getUserInfo()`
- Username now uses custom name if set, falls back to Waze username
- Custom username saved to localStorage

### v2.1.0 (2026)
- Migrated to official WME SDK
- Removed WazeWrap dependency
- Uses modern `sdk.Sidebar.registerScriptTab()` API
- Implements `wme-update-request-panel-opened` event
- Better error handling

### v2.0.0
- Complete rewrite with customizable templates
- localStorage support for persistence
- Dynamic placeholder system
- WME sidebar tab interface
- Reset to defaults button

### v1.0.0
- Initial release
