# 16-Jan-2023
- keylayout: Fix button mapping for headphone control *again* 
- rootdir: Enable suspend to RAM;
- vendor: QPR1 related fixes
- camera: Disable QTI perf lock usage in camera HAL
- render: OpenGL is back for a smoother/fast render
- init: Say goodbye to config_avoidGfxAccel as it responsable for some ui glitch's
- rootdir: Remove unnecessary QTI logkit directories
- wcnss: Clean up WCNSS_qcom_cfg.ini
- rootdir: Drop nqnfcinfo service
- powerhint: Adjust most part of configs for less consumption but still smooth

# 25-Dec-2022
- blobs: Update RIL stack
- system: Improvements on smooth and ram management
- parts: Fix compilation for QPR1 merge
- manifest: Uprev android.hardware.radio to 1.5
- rootdir: set default wifi country code to '00'
- props: Set some graphic/lmk configs
- Fixed camera freezes

# 18-Nov-2022
- Improved phase offsets configuration in order to improve smoothness;
- Fixed Sound Amplification Control from Xiaomi Parts;
- Fixed wallpaper zoom tune option;
- Disabled Skia tracing by default;
- Dropped WFD protected buffers support;
- Mapped Button Jack keylayout to fix headset button control;
- Added system call to the SE whitelist;
- Allowed syscalls needed by OMX component;
- Added permissions for RCS service;
- Added net_raw permissions for time_daemon service;
- Updated some rootdir configs;
- Disabled safe volume everywhere, not just the US;
- Show memory usage in app info;
- Used S theme in thermal settings;
- Fixed incoming calls;

# 15-Oct-2022
- overlay: Don't show vendor mismatch message
- props: Enable zygote critical window property
- bluetooth: configs: Drop component overrides
- bluetooth: props: Set BT device name via sysprop
- bluetooth: Remove bdroid_buildcfg.h
- XiaomiParts : Switch to new Xiaomi Parts implementation;
- ueventd: Set permissions for KGSL sysfs node;
- libhidl: Move to libhidl shim in hardware/lineage/compat;
- overlay: Define multiple vibration intensity levels config for T;
- bluetooth: Move Bluetooth power overlays to sysprops and power_profile;
- props: Switch to threaded Skia render engine backend;
- blobs: Prebuilt libtinyxml from miui_lavender_V12.5.3.0.QFGMIXM
- rootdir: Boost performance during bootup
- manifest: Drop android.hardware.tetheroffload.config
- overlay: Update night display configuration
- fstab: Set readahead_size_kb=128 to partitions
- rootdir: Stop bootanimation service after boot
- fstab: remove 'quota' option
- init: Enable config_avoidGfxAccel for 3GB variants
- overlay: Switch to AVC 3.1 for screen recording
- props: Disable client composition cache

# 15-Sep-2022
- Intial A13 Release
- Rootdir: Move ueventd.qcom.rc to /vendor/etc
- Props: Adapt BT Configs for A13
­- Drop Iorap
- Fstab: removed 'quota' option
- Switched to Dora Clang
­- Rootdir: Stop bootanimation service after boot
- Overlay: Pin renderscript blobs to memory
- Overlay: Update night display configuration
- Fstab: Set readahead_size_kb=128 to needed partitions
- Fstab: Removed unsupported fstab flag
- Manifest: Drop android.hardware.tetheroffload.config
- Rootdir: Boost performance during bootup
- Bluetooth: Remove non-existent libldacBT_{bco,dec} build rules
- Dropped script to reorder blobs list from DT
- Dropped android.hardware.health@2.1-impl.recovery package
- Prebuilt libtinyxml from miui_lavender_V12.5.3.0.QFGMIXM
- Sepolicy: Label qcom extcon sysfs
- Overlay: Switch to threaded Skia render engine backend
- Service: Revert Disable Chimera.GmsIntentOperationService
- XiaomiParts: Bring back Kcal and Thermal Settings

# 27-Jul-2022
- Clean Flash Mandatory
- Fix adoptable storage problem
- gps: Update GPS config for S
- overlay: Unpin updatable-media from memory
- overlay: Drop deprecated overlay
- overlay: Add support for Smart Pixels
- Copy Modified libprocessgroup configs to vendor * Schedtune
- Makefile: Inherit several Android Go configurations
- Bring back vendor RenderScript implementation
- props: Move IORapd configs to product
- Pull QTI Thermal from LineageOS and adpat to lavender
- DeviceSettings: Drop Thermal and Kcal configs
- Import apn configs from lineage
- sepolicy: Address smart charge denials
- Add overlays/node for smart charging

# 12-June-2022

- Pick up USB configurations from QCOM
- Bring IFAA back in tree
- Add OpenGL ES and Vulkan dEQP feature flags
- Modify Vulkan and OpenGL version to 2020-03-01
- Init: Drop no longer necessary libbase include dir
- Speed profile services and wifi-service to reduce RAM and storage
- Always preopt extracted APKs
- Strip off some debug packages
- Disable dexpreopt minidebuginfo
- Use speed tuning for performance critical applications
- Sepolicy: address surfaceflinger denials
- Add vndservicemanager explicitly
- Enable dex2oat64 to do dexopt
- Build all extra VNDK versions
- Sepolicy: Allow system server to getpgid zygote
- Overlay: Use CarrierConfig CSP boolean
- Disable debug.sf.recomputecrop
- Delete /data/system/package_cache after updates
- Sepolicy: Address iorap denials
- Don't warn user about FC in Google TTS
- Limit screen recorder's framerate to 60fps
- Import sf offsets from Coral android-vts-12.1_r2
- Set the maximum WFD resolution to 1080p@30
- Compact cached app heaps in the background
- Allow more cached apps in the background
- Disable remote Keygaurd animation
- Disable Chimera.GmsIntentOperationService
- Fix wi-fi permissions
- Add AOSP RCS packages
- Enable HWUI_COMPILE_FOR_PERF
- Import brightness overlays from MIUI
- Disable SDM Scalar
- Revert some uneeded changes
- Improve boot time and pull in bootanim display time
- Delete class_main init shell script
- Optimize package manager dexopt properties
- Optimise dex flags
- Update surfaceflinger props
- Enable UI touch haptic feedback by default
- Set the automatic brightness mode off by default
- Disable bluetooth by default
- Disable UI touch sounds by default
- Disable ART debug
- Libperfmgr: Drop not supported feature
