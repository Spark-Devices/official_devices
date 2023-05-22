# Clean flash (Coming from a different ROM)
- Download ROM
- Download Custom Google Apps Package (Like Nikgapps core/basic or Mindthegapps) if the ROM is Vanilla variant
- Reboot to Recovery
- Wipe System, Data, Vendor, Cache, Dalvik/ART cache partitions
- Flash latest stable firmware v11.0.3.0 before flashing ROM
- Flash ROM zip
- Flash Custom Google Apps Package if the ROM is Vanilla variant
- Reboot to system

# Dirty flash (Updating to a newer build)
- Download the new update ROM zip
- Reboot to recovery
- Do not wipe anything
- Flash the new update ROM zip
- Flash the same Custom Google Apps Package again you flashed before (For vanilla users)
- Flash Magisk again if you are rooted before (For rooted users)
- Wipe Cache and Dalvik/ART cache
- Reboot to system

# Notes
- On GApps ROM variant Google Apps are included, don't flash a separate Custom Google Apps package.
- ⚠️ BOOTLOOP SITUATION: If you are coming from stock/custom MIUI or any ROM which had data ENCRYPTION, you will face bootloop and can not boot into the system. In such case you need to FORMAT data after flashing the ROM. Otherwise the ROM won't boot.
- Things to keep in mind before format: Formatting your phone will wipe all the data. This data includes photos, videos, documents, applications, games, call logs etc. That's why you should make sure to have a backup before format. You can copy your necessary files on a pendrive, sdcard, PC and also can save large media files on cloud storage like Google Drive or OneDrive. Restoring your data from this backup is easy.
- For detailed instructions: https://github.com/anandhan07/Release/blob/main/Flashing-instructions.md
