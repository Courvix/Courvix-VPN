# Changelog

Documenting updates to the Courvix VPN client

## [1.0.5] - February 4 2022

## Added
- Users can now easily switch servers without having to first manually disconnect from servers. The disconnect is handled on switch.
- Useragent is being added to web requests to API to better conform to standards and prevent firewall false positives
- Discord RPC now contains timestamps
- Minimize will now move the client to tray

## Updated
- OpenVPN installer has been updated to a newer version
- Error logging improvements

## Fixed
- Discord RPC has been fixed
- Client will no longer retain cached server configs which has caused issues in regards to config updates & failures

## [1.0.4] - January 23 2022

### Added
- Logs should now be visible on errors so you don't have to go searching for them

### Updated
- Updated packages, including OpenVPN lib by Toshi which should fix some bugs
- Server list now fetches from API URL
- OpenVPN is now found with registry path, not by looking in the default install location

## [1.0.3] - July 7 2021

### Changed
- Server list now displays enabled servers only via the ("enabled") JSON value

### Fixed
- Discord RPC is now forcefully disposed on exit to prevent ghosting

## [1.0.2] - July 3 2021

### Added
- Added a version label 

### Fixed
- Fixed a bug with the automatic update feature where the previous executable was not deleted from the Temp folder causing automatic updates to fail

## [1.0.1] - July 2 2021
### Added
- Added minimize control box
- Added hover color to the server in the dropdown box.
- Added hover color to control boxes
- Added connecting indicator next to status
