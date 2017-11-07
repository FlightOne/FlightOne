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
