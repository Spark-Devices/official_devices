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
