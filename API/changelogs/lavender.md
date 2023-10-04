# 04-Oct-2023
- Fixed USB Tethering
- Set swappiness from kernel side
- Remove zram cold page writeback file
- Write 0 for zs_handle and zspage when configuring zram
- Enable ZRAM deduplication feature
- Decreased zram to a fixed-size of 2gb
- Properly label /sys/kernel/qvr_external_sensor/fd
- Fix adm buffering size
- Update CarrierConfig from LA.UM.10.2.1.r1-04000-sdm660.0
- Import QTI datastatusnotification from FP3
- Remove duplicate SIP+VoIP permission
- Decrease battery charging temperature thresholds
- Set userspace lmkd properties
- Satisfy EPPE enforcement
- Force pre-5.10 devices to treat 170M as sRGB in SF
- Extend buffer size to 256kb for offload playback
- Add DPM props
- Compact cached app heaps in the background
- Remove activity_recognition libs
- vmscan: Go back to default swapiness level´s
- ion: Limit concurrency of workqueues freeing buffers asynchronously
- defconfig: Enable powersave and userspace cpufreq governor
- defcongif: Disable slmk and enable userspace lmk
- Revert "block: remove legacy IO schedulers"
- defconfig: Enable CFQ Group Scheduling support

# 31-Aug-2023
- Bring up changes for kernel 4.19
- Adress denial's needed on 4.19
- Switch to source-built mlipay interface
- Move back to Xiaomi power AIDL HAL
- Reorder makefiles respecting alphabetical order
- Move to common IFAAService
- Move to common Xiaomi fingerprint HIDL
- Label FPC/4.19 nodes recursively
- Labeled missing wakeup nodes
- rootdir: Update qcom.post-boot from S62Pro
- Adapt light HAL for k4.19
- Updated media and audio qcom-caf hals from sdm660 tags
- Support new ANT stack
- Set PRODUCT_SET_DEBUGFS_RESTRICTIONS
- Adapt sdm660 powerhint to k4.19
- Adjust msm_irqbalance prio
- Add glink lpass irq to ignored list
- Don't configure zram in QCOM's init post boot script
- Switch to QTI USB 1.3 HAL and fix some vendor/product id
- Switch to FBEv2 emmc optimised encryption
- Update most blobs from Honeywell/hon660 and qssi;
- Update Gps stack from LA.UM.11.2.1.r1-02500-sdm660.0
- Build mtdservice interface lib from source
- Update mlipay from lavender V12.5.7.0.QFGCNXM
- Import HotwordEnrollment from blueline-user 12
- Update rootdir from LA.UM.9.2.1.r1-08000-sdm660.0
- Update most configs from Honeywell/hon660
- Properly disable phantom process killing
- manifest: Add FCM to satisfy vintf check
- Create dummy libldacBT_bco
- Comunize cnss-daemon and thermal
- Switch to two-stage init mounting
- Use logdump as metadata partition
- Include/flash DTBO image
- Fixed USB-C Dac
- Fixed adsprpcd logspam
- Fixed some wakelocks
- Suppress imsdatadaemon denials
- Switched to Pixel Powerhal from android-13.0.0_r3
- Adapted Pixel Powerhal for sdm660 usage
- Updated our powerhint
- Enabled MGLRU configs
- Adjust zram and swapiness

# 25-May-2023
- Tell vold we are done when we are actually done
- Defer triggering WiFi load to HAL
- Move qti_whitelist.xml to /system_ext
- Give proper permissions for /dev/diag
- Undefine BOARD_HAS_QCOM_WLAN
- Revert Wifi PowerSaveOffload configs
- Nuke DPM libshim and related
- Deduplicate handheld_core_hardware.xml copy rule
- Use MIUI poweroff charging animation from vayu
- Remove unused tcp property change actions
- Drop mediaextractor seccomp policy
- Revise mediacodec seccomp policy
- Improved our brightness logic

# 24-Mar-2023
- Set HWC setColorTrasnform as available

# 23-Mar-2023
- Cleanup all trash around DT
- Switch to pixel powerhal
- Rework perfd logic
- Simplify power hint's
- Drop all trash around Xiaomi Parts implementation and set basic Doze, Dirac and Thermal configs (what is really needed)
- Update thermal blobs from lavender lavender V12.5.3.0.QFGMIXM and LA.UM.8.2.r1-06200-sdm660.0
- Switch back to default aosp render (opengl) since skiagl it's causing systemui crashes following this
- Enable prefer_idle as it can ease cpu freq and decrease energy consumption
- Tune blkio as on google devices
- Tune schedutil up/down ratelimits
- Give the GPU more time to render the UI, resulting in less janks/lag
- Fix PowerOffAlarm
- overlay: Remove Manage Mobile Plan
- Disable SF composition prediction model on 5.4 and lower
- msm: camera_v2: Revert some patch's

# 28-Feb-2023
- thermal: Drop redundant qti implementation
- thermal: Update thermal blobs from LA.UM.8 and lavender V11.0.1.0.QFGMIXM
- system: Drop critical flags
- light/qpnp (DT/Kernel): Update internal structure logic from Parvinder Singh implementation
- overlay's: Introduce a new structure
- BC: Disable flatten apex logic

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
