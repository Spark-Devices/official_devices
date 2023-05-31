# 31-May-2023
- Add blkio tuning from sunfish
- Dolby: Update Permissions
- Disable QTI perf lock usage in camera HAL
- fixup! value for debug.sf.enable_egl_image_tracker
- Enable debug.sf.hw 
-  default color mode to automatic
-  Overlays: add vendor-defined color mode as well

# 31-May-2023
- Add blkio tuning from sunfish
- Dolby: Update Permissions
- Disable QTI perf lock usage in camera HAL
- fixup! value for debug.sf.enable_egl_image_tracker
- Enable debug.sf.hw 
-  default color mode to automatic
-  Overlays: add vendor-defined color mode as well

# 19-Mar-2023
- removed QTI perf
- update blobs from 14.0.7.0EU
- Fix missing display config path
- add missing vib_cal lib
- Revert to previous color modes
- revert back to old color modes settings
- Fix YT video 2k/4k playback issue
- tuned dolby sound 
- Correct SoC manufacturer name
- Compile out missing deps for libstagefrightdolby
- Move to Qualcomm USB Audio Policy configuration
- revert lahiana drivers (now can flash infinir kernel)
- Enabled Qualcomm Truewireless and TWS+ feature 
- Add advanced_sf_offsets configuration
- Toggle Display Has HDR
- Rework mi_thermals sepolicy 
- Fix path for msm-irqbalance config file
- enable VoLTE and VoWIFI support for Movistar

# 11-Mar-2023
- Implement DC Dimming support
- Define OEM fast charge sysfs node
- Label more battery supply & wakeup nodes
- Label remaining power supply nodes
- Adress a bunch of denials
- resolve health HAL denials 
- Import Xiaomi TouchFeature service
- Add touch profiles for gaming and benchmarking
- Use game thermal as fallback for GameSpace's listed apps
- Set network mode to Global by default
- Enable Rich-Communication Services 
- Import Xiaomi DisplayFeature service 
- Use QCOM implementation for audio effects
- Switch to Xiaomi Vibrator implemetation & Update VibratorFeature libs from Miui Munch V14.0.1.0
- Switch to vendor-defined color modes
- Import QTI Mediacodecs
- Import and switch to QTI Perf system
- update QQS footer and offset values
- Import displayfeature props
- Import all Display Calibation configs
- update Dax-Default
- Enable voNR Calls support
- Use FUSE passthrough mode by default

# 15-Jan-2023
- Add advanced_sf_offsets configuration. 
- Tune powerhint - wifi: No BSS flush for 2018 devices. 
- Set default Bluetooth name same as device market name. 
- remove F2fsRecessModeEnable from powerhint. 
- Dolby: Use correct prop for android 13. 
- Remove inexistent lib from pinner list. 
- Import missing audio prebuilts - Wip camera motor remnants. 
- Tune dalvik values - update graphics_composer rules. 
- Set correct default icon to per-app refresh rate.
- audio: fixup audio io policy voip_rx flags.
- Set BOARD_USES_ADRENO to true.
- Make dolby work on BT.

# 21-Dec-2022
- Updated more Blobs from 13.0.8.0
- follow status bar height on keyguard
- update punch-hole cutout
- update rounded corner value form AOSPA 
- Update deprecated powerprofile items
- wifi: Create another interface during driver load
- Import additionally libcdsprpc_system libs
- Import 32bit adsp/cdsp default listener libs
- Do not use MMAP For Audio
- Import more props for ril powersaving
- Disable QCRIL power saving
  (this should solve slow internet speed for some users)
- disable SF backpressure 
- Add parameters for Hotspot 2.0
- Enable support for IEEE80211AX &IEEE80211AC
- Allow more cached apps in the background 
- Drop Qualcomm WFD 
- Don't limit inodes on /system_ext
- Inherit several Android Go configurations
- Disable client composition cache
- Switch to Vulkan UI renderer
- Add sysprops for touch improvements and smoother scrolling and better responsiveness 
- Tune Adaptive Suspend parameters
- Update pinner configuration
- Enable AutoHBM service on BootCompleted
- Set bluetooth.device.default_name to 'Poco F3'
- Enable suspend to RAM 
- Import userdata tuning from oriole
- Disable kpti
- Localise NTP to improve GPS TTFF
- gps: Revert oem changes

# 16-Nov-2022
- fix blur not showing 
- removed Gcam and  Graphene OS cam

# 14-Nov-2022
- Enabled system info
- Drop updateable GPU drivers
- Use HintManager for HWUI
- Disable BT SAP server
- Fix Deepsleep with bluetooth on 
- Power: Decrease launch boost to 3sec
- Kill IMS logspam with fire
- Add xiaomi cit sensor service
- Import and switch to qti vibrator effect
- Enable the pre-rendering feature
- Optimise dex flags
- Optimize package manager dexopt properties
- Compile HWUI for performance
- Properly declare our platform info
- Drop palm sensor inits
- Drop VULKAN_DEQP_LEVEL handling
- Don't spam logspam when bt headset is connected
- Allow citsensorservice use sysfs_leds
- Added Dirac
- Added one plus Dolby
- update Audio config from 13.0.8.0 EEA
- Update CarrierConfig from munch V13.0.4.0.SLMMIXM
- Added HBM
- Added Miui camera
- address some sepolicy denails
- drop lineage power profile and import AOSPA Trees Power Profile
- Switch to N0 kernel 
- Switch to WeebX clang 16
- ThinLTO support system wide

# 15-Oct-2022
- Initial build


