# 11-Oct-2022
- Fix usb dual role switch (data transfer issue)
- Include FM radio app

# 12-Sep-2022
- Initial A13 release

# 17-Aug-2022
- Disable QTI perf lock usage in camera HAL

# 23-Jul-2022
- Switch back to OpenGL for UI rendering
- Fix artifacts in videos in some apps like Instagram
- Fix Smart Charging
- Support Smart Pixels
- Use directBootAware for parts
- Fix SEPolicy and stop ignoring neverallows
- Add translations in parts
- Update wireguard
- Merge some changes from CAF in kernel

# 22-Jul-2022
- Switch back to OpenGL for UI rendering
- Fix artifacts in videos in some apps like Instagram
- Fix Smart Charging
- Support Smart Pixels
- Use directBootAware for parts
- Fix SEPolicy and stop ignoring neverallows
- Add translations in parts
- Update wireguard
- Merge some changes from CAF in kernel

# 10-Jun-2022
- Enable haptics for text cursor
- Address Soter denials
- Add missing deviceInfoServiceModule
- Modify automatic brightness
- Add BOARD_HAS_QCA_FM_SOC cflag
- Add missing FM prop
- Merge changes from CAF in kernel

# 16-May-2022
- Support multiple levels of vibration intensity
- Don't pin launcher app and updatable media in memory
- Allow apps to get aux camera prop
- Enable IORap tracing and prefetching
- Enable Zygote preforming
- Enable some frequencies for GPU in powerhint
- Disable Bluetooth by default
- Turn on compressed apex
- Disable vsync for CPU rendered apps
- Disable blurs during app launch
- Add Livedisplay
- Switch to Livedisplay's implementation for HBM (automatic mode included)
- Filter and remap display modes in Livedisplay (removing useless ones and rename the others to make them more user friendly)
