# Troubleshoots

### Your profile can not be used because it is from a newer version of NW.js
> Your profile can not be used because it is from a newer version of NW.js.  Some features unavailable. Please specify a different profile directory or use a newer version of NW.js.

You need to delete old configurator data folder from your PC. Data directory is in following directories according to your platform:

* Windows: `%LOCALAPPDATA%/RaceFlight/`
* Mac: `~/Library/Application Support/RaceFlight/`
* Linux: `~/.config/RaceFlight`

![alt text](troubleshoots_1_1.png)


### Internal HID error

When you receive *Internal HID error* message it could possibly means that you disconnected board during data transfer or your board out of sync. Usually disconnect and then reconnect board helps in this situation.
