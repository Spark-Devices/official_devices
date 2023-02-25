# 25-Feb-2023
- Switched to Revamped FMRadio (credits: iusmac)
- Improved headset and earpiece volume a lil bit.
- Increased call volume steps to 15.
- And some miscellaneous fixes.

# 15-Jan-2023
- Fixed keyguard statusbar overlapping on Quick settings.
- Fixed Privacy indicator dot spacing.
- Removed BATTERY_CHARGING_CTL from thermal-engine.conf

# 14-Jan-2023
- Fixed no 2G/GSM option in Preferred Network Types.
- Fixed Android Auto in GApps builds.
- Removed unwanted graphics props.
- Improved overall smootheness.

# 05-Jan-2023
- Added Non-Root ViPER4Android FX audio equalizer (means works without root).
- Addressed some camera denials.
- Improved wifi connection stability.
- Fixed 5GHz Hotspot.
- Fixed mic in discord and other voip apps.
- Fixed vulkan API support.
- Fixed Bootanimation lag.

# 16-Nov-2022
- Fixed freezing issues in some cases.
- Tuned surfaceflinger props for smoothness and better response.
- Fixed notification delay in some apps.

# 15-Nov-2022
- Unitrix kernel 4.9.333
- Updated Display/Graphics stack from LA.UM.10.6.2.r1-01600-89xx.0.
- Updated Audio, Display, Media HALs from LA.UM.10.6.2.r1-02500-89xx.0.
- Updated Carrier configuration from LA.UM.10.6.2.r1-02500-89xx.0.
- Switched to Stock MIUI v11.0.2.0 Build fingerprint.
- Fixed excessive battery drain.
- Fixed stuttering while app launch in launcher3
- Fixed Bluetooth Device name space breakage.
- Disabled skia tracing record.
- Disabled GPU intensive UI effects for all.
- Enabled QS System info.
- Enabled Memory usage in App info.
- Switched to AIDL DRM services.
- Silenced several logspams.
- More display rounded corner.

# 12-Oct-2022
- Unitrix 4.9.330.
- Fixed mobile data for Non-Indian Users.
- Fixed mobile data in sim2.
- Fixed no ringtone in BT headset.
- Fixed Display rounded corners.
- Switched Audio HAL to V7.
- Improved wifi scan.
- Tuned surfaceflinger to improve window transition and reduce stuttering.
- Optimized system performance and improved stability.

# 13-Sep-2022
- Initial A13 Release

# 20-Aug-2022
- Dropped redundant zram writeback.
- Set 50% zram of the total RAM.
- Set swappiness to 60.
- Tweaked dalvik props for 3GB & 4GB variants properly and moved it into libinit.
- Imported ACDB's from various msm8953 devices.
- Improved sound quality and volume for loudspeaker and headset/headphones.
- Fixed poor recording quality of voice recorders.
- Fixed mic distortion in voice calls.
- Disabled blur again.
- Improved indoor GPS accuracy.
- Imported perfd blobs from stock miui to handle perf lock properly.
- Fixed battery drain due to wifi.
- Reduced UI lag while screenrecording.
- Tuned surfaceflinger duration props for better performance.
- Optimized system performance and improved stability.

# 24-Jul-2022
- Unitrix Kernel 4.9.324.
- Fixed No audio playback in loudspeaker while playing games.
- Imported missing ACDB's from tissot.
- Fixed mic related issues for some social media apps.
- Fixed battery drain and overheating due to gms service.
- Fixed thermal-engine regression on certain cases.
- Updated CarrierConfig from LA.UM.10.6.2.r1-02200-89xx.0.
- Fixed the issue that removing 'zero' from mcc and mnc values in CarrierConfig.
- Optimized dalvik for smooth app operations.
- Moved surfaceflinger props to system/build.prop.
- Dropped triple frame buffers.
- Removed IORapd, trim & bservice properties.
- Improved RAM management.
- Added a temporary workaround for Dual SIM VoLTE configuration switch (ie you no longer need to reboot, just toggle Airplane Mode on and off after 'switch data card' tile in qs).
- Updated CNE, DPM, QMI, Telephony stack, WiFi, Time services, Power-off alarm, Peripheral manager blobs from LA.UM.9.6.3.r1-06200-89xx.0.
- Updated FMRadio blobs from LA.UM.9.6.3.r1-04400-89xx.0.
- Updated DRM + Widevine from Coral.
- Dropped redundant blobs.
- Lots of init fixes.
- Optimized system performance and improved stability.

# 12-June-2022

- Switched to User Build.
- Unitrix Kernel 4.9.317.
- Bump to June raven fp.
- Updated audio configs from LA.UM.9.6.2.r1-04800-89xx.0
- Removed obsolete mixer_paths.xml.
- Use audio_policy_volumes.xml from AOSP.
- Restored stock msm_irqbalance.conf
- Fixed high battery drain in some cases.
