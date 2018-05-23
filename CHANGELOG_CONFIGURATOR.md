#### 1.1.109

- Removed `dshot1200` choose when ESC type is blheli_s
- Removed calibrate motors when ESC type is blheli32
- Added Autoupdater for Windows and MacOS versions.

#### 1.1.108

- Added ESC tab with ESC info and change motor direction wizard for Blheli 32
- Fix some quick defaults
- Small UI fixes and improvements

#### 1.1.107

- Fixed issue when number of lines for OSD not change based on OSD type

#### 1.1.106

- Added blheli32 telemetry switch
- Added Proshot 32khz esc protocol
- Removed DShot150 esc protocol
- Increase number of lines for OSD from 13 to 16
- Added OSD Type dropdown on Configuration page
- Small UI fixes
- Set minimum fc version to 1.1.106

#### 1.1.102

- Added quick change filter levels button on PID Tuning page

#### 1.1.101

- Added expert mode option in settings
- Added Average ESC temp, ESC eRPM, ESC current OSD options
- Update defaults on PID Tuning page
- Fixed issue with version check
- Move Update ESCs wizard to Configuration page

#### 1.1.85

- Added 'Proshot' esc protocol on Configuration page
- Added 'Disabled' filter type option on PID Tuning page

#### 1.1.80

- Added 'Fake Kalman Filter' and 'RC FIR2 Filter' on PID tuning page
- Removed 'Predictive Filter' for D filter
- Small bug fixes

#### 1.1.46

- Hide frequency filter if user pick predictive on PID tuning page

#### 1.1.45

- Added ability to restore previous settings after flash even the fc version not supported
- Rename gyro smoothing 'Low' to 'Off'

#### 1.1.44

- Removed ESC signal smoothing switch from PID tuning page
- Changed filter types

#### 0.590.0

- Improve motor direction wizard for blheli32
- UI improvements

#### 0.586.0

- Voltage offset range changed from 0.5-1.5 to 0.75-1.2. Added percent sign
- Fixed issue when news not shown correctly
- Added "Voltage Per Cell" option for OSD layout
- UI improvements
- Set minimum fc version to 0.586.0

#### 0.575.1

- Added "Current" option for OSD layout

#### 0.575.0

- Added Hebrew language support
- Some bug fixes for Linux
- Update 7in defaults
- Flight One rebranding

#### 0.572.1

- Fixed issue when saving not worked on configuration tab

#### 0.572.0

- Fixed issue when min fc version not worked on first launch
- Set rc_smoothing to 1 when New RC Smoothing checkbox changed
- Small UI issues

#### 0.571.0

- Added switch to enable new rc smoothing
- Configurator can show incompatibility with new firmwares now
- Changes on configuration page will save before go to cleanflight passthrough
- Added voltage offset on configuration page
- Import settings from unsupported firmware versions are now available with warning
- Small UI fixes

#### 0.570.0

- Removed Filter level field from PID tuning page
- Update quick defaults

#### 0.569.1

- Fixed issue when motor direction not save for blheli32 wizard
- UI improvements for passthrough 

#### 0.569.0

- Removed lowpass_bw variable
- Set minimum fc version to 0.569.0

#### 0.565.1

- Some UI changes
- Translation improvements

#### 0.565.0

- Added LED with USB switch on configuration page
- Old setting automatically save to file before flash(note that if your previous settings is supported by configurator it will ask you to import settings automatically). Path for saved backups:
```
    Windows: %LOCALAPPDATA%/RaceFlight/Default/backups/dump/
    Mac: ~/Library/Application Support/RaceFlight/Default/backups/dump/
    Linux: ~/.config/RaceFlight/Default/backups/dump/
```
- Added cleanflight passthrough button on configuration page
- Fixed issue when motor reverse wizard show error when dshot mode was previously enabled
- Previous setting after flash can be restored even configurator was closed now
- Fixed export new rate variables
- Improved translation
- Performance and security updates

#### 0.560.0

- Added new filter types
- Added gyro smoothing on PID tunning page
- Added vtx power on configuration page

#### 0.524.0

- Added low pass settings on PID Tuning page
- Added kill channel and vtx channel dropdown on configuration page
- Removed Startup Tone option from ESC page
- Fixed issue when after flash formatting window not closed
- Set minimum firmware version to 524

#### 0.500.4

- Set tx3 by default in interview wizard
- Added throttle curve on PID Tuning page
- Hide ESC tab and Update ESC wizard for all ESCs except blheli_s
- Modify wizard 6 for other ESCs
- Update Blackbird FPV rates
- Added "Brushed 8khz" esc protocol
- Fixed small UI issues

#### 0.500.3

- Fix typos, change images
- Small UI fixes

#### 0.500.0

- Wizard 4 set minthrottle to 1012 and maxthrottle to 1870 for each motor
- Added competed or not flag to each wizard
- Modified Calibration wizard to enable txprogramming before calibration and disable after
- Added ability to reset old settings after flash.
- Sign OSX app, so mac os users will not receive warning message with first launch
- Added arming issues wizard on Setup page
- Added setup manually page to detect receiver wizard
- Added esc type step in interview, to modify wizards based on your ESC. You can also change it on configuration page
- Improved translation and analytics
- Set minimum fc version to 0.497.0

#### 0.426.2

- Fixed issue with motor mapping in last wizard and saving
- Small bug fixes
- Updated Korean language

#### 0.426.1

- Fixed issue with importing whole dump
- Small UI fixes

#### 0.426.0

- Added export options
- Fixed issue when import dump from file sometimes failed
- Fixed issue with math calculation for some value on PID tuning page
- `rap` variables are not editable from PID tuning page anymore

#### 0.420.3

- Fixed incorrect display value for `Current draw`
- Fixed display decimals on PID tuning
- Improved users tune preset service (https://raceflight.com/rf-configs/)

#### 0.420.2

- Fixed issue when profile name not display correctly after save
- Added "Brushed" option to ESC protocol on configuration page
- Updated Korean language
- Small UI fixed and improvements

#### 0.420.1

- Added possibility to flash firmware online
- Added possibility to upload/share user configs on https://raceflight.com/rf-configs/  (Alpha testing for now) 
- Fixed issue when rc smoothing can be less then 1 after applying quick tunes
- Fixed issue when board do not load into Flight controller mode after flashing firmware in DFU

#### 0.420.0

- Added Pilot name field on configuration page
- Changed CG Adjustment defaults from 1 to 100
- Added table view for rate dps on pid tuning tab
- Added Force Update ESC button on ESC tab
- Added OSD configuration wizard
- Added Internal OSD option for OSD dropdown on configuration page
- Small UI Fixes
- Set minimum fc version to 0.420.0

#### 0.419.3

- Removed warning when configurator detects more then one switch movement with mode wizard. It will select lower number channel.

#### 0.419.2

- Fixed issue #232
- TPA value could be editable with keyboard, by clicking on them
- Fixed small UI issues

#### 0.419.1

- Fixed issue when some users have incorrect defaults with first load
- Added "Load OSD Character Map button" on Configuration page
- Changed layout for Configuration and ESC pages
- Added confirmation window when you remove mode via wizard
- Updated Korean language
- Fixed small UI issues

#### 0.418.0

- Fixed voltage decimal point

#### 0.416.0

- New layout for Setup page
- Fixed bug when PIDs in non percent mode not changed with quick change button
- New PID Layout
- Fixed defaults
- Fixed Current Draw and Consumed values on Configuration page
- Fixed small UI issues

#### 0.409.0

- Added CRSF options for receiver protocol on Configuration page
- Quick change filter levels now show based on filter type

#### 0.402.0

- Added options to change layout for modes(via wizards or via sliders)
- Fixed issue when mode is not set via wizard on some radios
- QUOPA modes now have only two options: `Automatic 2 motor mode` and `Manual 2 motor mode`

#### 0.400.0

- Changed setup page layout
- "Setup radio" wizard improvements
- Fixed issue when modes not save while import
- Fixed arming issue after wizard
- Remove blheli_32 from wizard
- Improve localization
- Update Russian and Korean language 
- Added voltage data on Configuration tab.
- Added Crossfire option on chose receiver page in interview wizard
- Fixed issue when scroll bar not appear in wizard 6
- Removed Enable digital precision mode on configuration page
- UI updates, small bug fixes
- Set min firmware version to 0.400.0

#### 0.375.2

- Added `bheli_32` support for motor direction wizard
- Added import/export quad settings from file menu
- Update French and Korean languages

#### 0.375.1

- Fixed issue when some defaults are not applied after wizard

#### 0.375.0

- Added warning window when you make changes, but forget to save them.
- Filter type now apply default values
- Small UI issues
- Set min firwmare version to 0.375.0

#### 0.374.2

- Fix issue when TPA values not applied in Setup wizard

#### 0.374.1

- UI improvements
- Fixed issue when TPA and some other variables not copied to another profile
- Filter type affect to omega variables now. If filter type is `Dynamic noise` then omega variables(`omega1_yaw` etc.) will be the same as filter level.
- Added 3 new fields(roll rap, pitch rap, yaw rap) on PID Tuning tab page

#### 0.374.0

- Fixed issue with empty craft_name field on configuration tab
- Fixed issue when 3D model on telemetry tab sometimes not appeared
- Improve IU for Setup FC wizard
- Fixed several UI issues
- Improve translation and analytics
- Set min firmware support version to 0.374.0

#### 0.364.1

- Fixed startup crash on OSX Mavericks
- Performance and security updates
- UI fixes

#### 0.364.0

- Improve Detect receiver wizard
- Improve Setup Radio wizard
- Fixed error with resetting telem data after Setup Radio wizard
- Fixed rare bug when board wont connect after error
- Improve error messages
- Added Filter type selection on PID Tuning page
- PID non percent values now editable

#### 0.363.0

- Added craft name option on configuration tab
- Update filters
- Fixed issue when some option not copied on PID tuning tab

#### 0.362.0

- Added more QUOPA Mode Style options(Automatic 4 motor mode, Automatic 2 motor mode, Semi automatic 4 motor mode, Semi automatic 2 motor mode, Manual 4 motor mode, Manual 2 motor mode)

#### 0.352.0

- Added shop tab
- Updated Korean language
- Added QUOPA Mode Style drop down to on the Configuration Page(options Automatic, Semi-Automatic, and Manual)

#### 0.326.0

- PID defaults changes
- Small UI fixes
- Set min firmware support version to 0.326.0

#### 0.324.0

- Update Korean language
- Fixed tpa curve slider bug, when max value was 100
- Small UI fixes

#### 0.320.1

- Update French language
- Added old(slow) download flight log method for people who has issue with their drives
- Added smartaudio select to interview page

#### 0.320.0

- Added "Crossfire telemetry on TX3" button on Configuration tab
- Changed "CPPM TX Pin" and "CPPM RX Pin" values on Configuration tab
- Changed/Remove some quick selection defaults

#### 0.317.1

- Fixed issue with connection on windows

#### 0.317.0

- Added News tab
- Changed Flight log download system
- startuppower, tempprotection and demag set by ESC wizard now
- Added .5 format support for input fields
- Fixed bug when white screen sometimes appear after connection
- Fixed issues when multiple devices connected
- UI Improvements
- Set minimum support firmware version set to 0.316.0

#### 0.314.1

- Added copy profile values button on PID tuning tab
- Added OSD options on Configuration tab

#### 0.314.0

- Added VTX control dropdown to select VTX device (#176)
- CG Adjustment increase max value to 1.1
- UI Improvements
- Performance and security updates

#### 0.307.0

- PID levels, rates, filter defaults will delivery from internet now
- Added "Current value" label on pid tuning tab
- Added "Demag" option on ESC tab (#164)
- Fixed issues with interview wizard
- Made more informative error messages
- Updated Korean and French languages
- UI fixes (#151)
- Performance and security updates

#### 0.302.1

- Fixed issue when GUI freezes if you select "yes" to help smooth stick movements
- Fixed motor noise test layout(#162)
- Improved Korean language
- UI improvements(#154) 

#### 0.302.0

- Added stepper widget for fields for convenient use on Tablets
- Fixed blackbirdfpv TPA profile values
- Add validation for all fields (#163)
- Added Korean language support
- UI fixes
- Added support for firmware version with profiles and without them
- Min support firmware version set to 0.300.0

#### 0.301.0

- Added multiple profiles

#### 0.300.0

- Fixed issue when you erase flash and indicator doesn't change
- Fixed UI adaptation on small screens
- Added Japanese language support
- Improve Russian language
- Added "ESC info" button on Configuration->ESC
- Added more tooltips
- Small UI fixes and improvements
- Added value labels for TPA sliders on PID tuning page
- Added "Roll deadband", "Pitch deadband", "Yaw deadband" on PID Tuning page
- Fixed small user interface issues
- Changed incorrect setting VTX mode in VTX wizard
- Changed OSD switch value from 5 to 4
- Changed motor layout in Configuration-Test motors wizard
- Improve Update firmware screen
- Added option to disable graphics accelration for configurator

#### 0.295.4

- Added button to share motor test results
- Fixed USART 3 TX for interview

#### 0.295.3

- Fixed VTX wizard
- Updated German language
- Made all video tutorials to open in browser instead

#### 0.295.2

- Fixed white screen bug on win32
- Update Spanish language

#### 0.295.1

- Set kd_rap to 55

#### 0.231.0
- Fixed issue #114, #118
- Added ability to control/test each motor(#51)
- Update radio setup UI
- "Help" tab back
- Update "Fix motor direction" wizard
- On PID Tuning tab now you can see real PID values
- Added "ESC Signal Smoothing", "CG Adjustment", "kD Limit", "kI Limit", "Yaw kD Filtering", "Roll kD Filtering", "Pitch kD Filtering" fields on PID Tuning tab
- Added "BlackBirdFPV" profile
- Added Smart curve switches

#### 0.230.0

- Improve "Setup flight controller" wizard
- Added profiles on PID Tuning
- Fixed UI bugs
- Set min TPA values to 1 for sliders
- Added ru lang support
- Fixed DFU bug
- Added tooltips and help screens
- Added setup board interview
- Added PID values not in percents
- Fixed DFU loading bar

#### 0.229.0

- Added rc smoothing
- Fix motor mapping
- Decrease application size
- UI improvements
- Changed RX protocol list
- Added tpa sliders on PID Tuning tab
- Added PID sliders
- Added TESTMOTORS wizard

#### 0.228.0

- Added "Order motor" step to "Fix motor direction" wizard
- Fix bug when unable to save old value in ESC tab without reload
- Prettify wizards
- Fix bottom toolbar styles
- Added TPA commands to the PID profiles
- Fixed DFU mode when sometimes screen doesn't change
- Added RC Smoothing slider
- Added field validation and tooltips for fields

#### 0.223.0
- Increment version to 223 to match RC13

#### 0.197.0

- Added VTX PitMode Type wizard
- Added license page
- Fixing translations
- Small bug fixes
- Moved "Update firmware" title to top
- Added 16000 option for frequency
- Fixed ESC start up power saving
- Fixed issues caused by not working motors or other problems on ESC tab
- Update *de*,*fr*,*es* translations 
- Added OEM (beep) tone
- Added Digital Precision Mode

#### 0.196.0

- Added telemetry tab
- Fix radio data on setup tab
- Fix motor order in motor direction wizard
- Cosmetic fixes
- Fix translations
- Fix issue #72

#### 0.195.0

- Added DFU flashing mode
- Added de, es, fr, sk, zh-cn languages
- Fixed motor calibration labels
- Fixed small issues
- Added frequency options
- Added SmartAudio and OneShot options

#### 0.194.0

- Added localization
- Added "Medium Low" and "Medium High" timing options
- Added "Quick change PID level" button and Rates default values
- Fixed "Reset" button on PID Tuning page
- Fixed Bootloader flashing file upload, that could stuck when incorrect file has been uploaded.
- Fixed "Update Firmware" button
- Improved "Setup", "Detect" and "Radio" wizards.
- Fixed "ESC" tab when it fails sometimes.
