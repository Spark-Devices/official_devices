# 30-Jul-2022
- Fixed 5g 
- Fixed video call
- Fixed wfd 
- Updated kernel (wild angel v76)

# 17th june 2022
- Adapt status bar after June patch
- Properly configure corner roundness
- switchto using xiaomi disp_param cmd command
- Implement LiveDisplay HAL
- Fix fingerprint wake-up animation
- Enable burnin protection
- Update adreno graphics blobs to v@0615_v3
- and many more check my trees for full changes

# 25th May 2022
- Removed advanced refresh rate tile (causes boot loop)
- Reduced flickering as much as possible 

# 16th May 2022
- Update blobs from Miui 13.0.4.0
- Add missing nqnfcinfo prebuilt
- AAC frame control enabled for hal implementation.
- Switch to source-built mlipay interface and mtdservice interface
- Enable TWS plus feature using persist property
- Enable Qualcomm TrueWireless™ Stereo
- Enable DPM Connection Tracking (CT) & Move DPM feature property to /system_ext
- sepolicy: Allow softwarecodecs work with gpu
- Import missing media_codecs_sw.xml
- Fix up libperfmgr crash on logs 
- Use TAS only for launch
- Resolve dexoptanalyzer denials
- Drop all component overrides
- Re-enable zygote preforking
- Update Feature enabler, Time services, ESE,Configstore,Gatekeeper, msm-irqbalance, TEE & TUI,SCVE blobs from LA.UM.9.12.r1-14100.01-SMxx50.QSSI13.0
- Update display blobs from LA.//UM.9.12.r1-14000-SMxx50.0
- added back dolby
- added live display
