# Clean flash (Coming from a different ROM)
- Download ROM.
- Download any Gapps Package if ROM is Vanilla.
- Reboot to Recovery.
- Wipe System, Data, Vendor, Cache, Dalvik/ART cache.
- Flash latest stable Firmware (Highly recommended to flash v11.0.3.0 stable firmware before flashing ROM)
- Flash ROM zip.
- Flash Gapps Package if ROM is Vanilla.
- Reboot to system.
- To get root access, Reboot to recovery after ROM setup and flash Magisk.

# Dirty flash (Updating to a newer build)
- Do not wipe anything.
- Flash new ROM zip.
- Flash the same GApps Package again you flashed before (for vanilla users).
- Flash Magisk again if you are rooted before.
- Wipe Cache and Dalvik/ART cache.
- Reboot to system.

# Notes
- On GApps ROM variant Google Apps are included, don't flash separately.
- If you are coming from MIUI or any encrypted ROM, Format data to remove encryption. Otherwise new ROM won't boot.
