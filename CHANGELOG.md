# [1.1.0] GTK4 & Multi-Tool Update

## Added
- Upgraded project target to .NET 10.0
- Completely migrated the UI from legacy GTK to native GTK4/Libadwaita (`GirCore.Adw-1`) for modern GNOME 4x styling
- Added automated `.tar.md5` extraction workflows to support Heimdall flashing
- Added automatic `.lz4` decompression support (via `unlz4`) during Heimdall partition extraction
- Added full support for the open-source `thor-flash-utility` via automated REPL shell commands

## Fixed
- Replaced the custom About dialog with a native `Adw.AboutWindow`, properly integrating the embedded app icon
- Fixed GTK window size scaling warnings by adjusting minimum window requests
- Fixed Heimdall failing on compressed Samsung firmware archives
- Fixed Thor execution flags conflicting with open-source syntax

# [1.0.0] Initial Release

## Added
- Odin
- ADB
- Google Apps
- Fastboot
- Firmware Update Server
## Removed
- N/A
## Fixed
- N/A