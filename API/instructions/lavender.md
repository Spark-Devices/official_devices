# Clean flash:
- Wipe system, data, vendor, cache, dalvik, metadata
- Format data
- Install 4.19 recovery provided on support group
- Enter manage partitions on orangefox configs, change Data & Cache partitions file system to F2FS
- Install rom
- Install your gapps package or other stuff if you are gonna need it later, remember recovery will not be decrypted, otherwise use a SDCard or USB OTG
- Reboot to system and voila!

# Updating to a newer build (dirty flash):
- Download rom update
- Reboot to recovery
- Enter on menu, connect your phone with pc and choose ADB & Sideload
- Execute adb sideload <rom package filename>.zip
- Or if you have a SD card, you can put the rom package into the SD card and flash it on recovery directly instead of using adb sideload.
- Wipe cache and dalvik
- Reboot to system and voila!
