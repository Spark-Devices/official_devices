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
- For detailed instructions: https://github.com/anandhan07/Release/blob/main/Flashing-instructions.md
