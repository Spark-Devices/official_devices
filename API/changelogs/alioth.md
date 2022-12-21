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


