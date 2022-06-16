# Clean flash:
- Flash recovery (link is above)
- Download ROM from the link above
- Reboot to recovery
- Format data
- Flash ROM Zip via adb sideload by following these steps
 - Connect phone to PC via USB
 - On phone, choose Apply Update > Appily via USB
 - On your PC download/make sure you have the latest adb from android-sdk-tools all unzipped to their own folder, then place the downloaded ROM zip in that same folder.
 - Still on your PC, open command prompt or PowerShell (or Terminal in linux) and type the following without the quotes , and replace <rom.zip> with the actual filename of the ROM zip "adb.exe sideload <rom.zip>
- Reboot and voila!

# Updating to a newer build (dirty flash):
- Update via OTA Updater, or
- Flash ROM zip using the adb sideload method above
- Reboot and voila!
