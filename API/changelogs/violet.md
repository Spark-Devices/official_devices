# 23-May-2023
- overlay: SystemUI -> SystemUIGoogle 
- Use speed tuning for performance critical applications
- Import multiple vibration intensity levels config for T 
- Set block_binder_thread_on_incoming_calls in product.prop 
- Configure default light sensor type 
- Remove aptX(HD) encoder shared libs
- Redefine bluetooth a2dp offload capabilities
- Use Clang 17.0.0 to compile kernel 
- Set 15 seconds as default screen timeout
- enable ro.hwui.render_ahead to 10
- audio: Correct routing order for voip output
- Use primary input sources for voip_tx 
- Checkout CarrierConfig to LA.QSSI.13.0.r1-08600-qssi.0 
- Switch to stock acdb loader libs
- Remove dsp. prefix from audio and video power profiles
- Fix deprecated power profile items 
- Update system blobs to LA.QSSI.13.0.r1-09400.01-qssi.0
- reorder blob script: Stop treating subdirs as special during sort
- Update vendor blobs to LA.UM.9.1.r1-12900-SMxxx0.0 
- Drop Neural Network stack
- Sync with stock audio props
- audio: Remove dynamic attributes from APS config
- audio: Set valid and supported channel mask for earpiece
- audio: Fix mic issues in apps like WhatsApp
- audio: Remove FM Tuner from input devices 
- audio: Add FM Tuner to voip_tx input
- Sync with stock audio configs
- set ro.sf.lcd_density=420 
- Enable VoLTE/ViLTE/VoWiFi for entire 470 mcc 
- audio: Enable 24-bit for primary output and deep buffer 
- audio: enforce 24-bit audio for offload playback 
- wifi: Increase max bss count 
- wifi: Disable BSS flush 
- Don't Remove Velvet and Chrome-Stub
- overlay: set combined QS to false
- overlay: Adjust overlays for recently added light capability
- Exclude lineage-sdk overlays from RRO
- Mics changes and improvement

# 21-Mar-2023
- Update clear speaker audio 
- Disable Stereo channel support for voip
- Checkout audio_io_policy from sweet
- Add compress recording configurations 
- Force show network traffic on statusbar 
- Restore pre a13 battery warning threshold
- Wifi Enable set channel on NDP setup 
- Wifi Configure correct overlay configuration
- Show battery percentage
- azure-Discombobulated+ kernel

# 26-Feb-2023
- February security patch 
- Implement keyhandler for fingerprint shutter 
- wifidisplay Disable protected buffers support  
- Add two channels for echo referece 
- Tune vibration pattern  
- Add Dolby Atmos (From Sony Device) 
- Enable world phone bool 
- Make the UI smoother 
- Enabe Battery Health  
- Enabe system info 
- Enable QR scanner shortcut in lock screen  
- xcalibur-v2 kernel  
- Nuke more packages (Google, Files, Chrome) 
- Show memory usage in app info 
- Improve Stability

# 15-Jan-2023
- Vibration & haptics setting crashing fixed

# 15-Jan-2023
- Fully rebased tree
- MiuiCamera included
- Uprev radio to v1.5
- Redesign FPS Info
- Set Window animation/transition scale to 0%

# 21-Dec-2022
- Add Max visible notification icons  
- smoother scrolling and better responsiveness  
- Set Google autofill service as default  
- Switch to Azure kernel  
- Fix Fingerprint Wake-up Animation   
- Implement Clear Speaker  
- Disable UI touch haptic feedback by default  
- Disabled dial pad tones by default  
- Disabled screen locking sounds by default  
- Enabled vibrate for calls by default  
- Disable sf auto latch_unsignaled  
- Enable display force split  
- Remove Graphene Camera  
- Other fixes and improvement

# 14-Nov-2022
-Drop overlays for Battery health 
-Adapt unsignaled buffer latch property to Android 13  
-Use HintManager for HWUI  
-Bring back build property for reduceOpsTaskSplitting 
-Remove AUDIO_FEATURE_ENABLED_PROXY_DEVICE  
-Remove references to a2dp module 
-Drop dead bt target 
-Drop prebuilt GoogleCameraGo 
-Debloated some packages 
-Drop duplicate SystemUI dex preopt  
-Reduce swapping aggressiveness to 10 
-Tune SLMK values 
-Added GrapheneOS Camera

# 12-Oct-2022
- Inital official A13 release
