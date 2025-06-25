## Restore System Partitions

> [!CAUTION]
> This only restores the system partitions on an existing formatted PSX HDD.
> Only the firmware version that has been installed before can be also restored on the console.
> If your firmware or console isn't mentioned here then you can ask in the PS2 Scene Discord for help.
> https://www.psx-place.com/threads/an-open-discord-for-discussion-solely-related-to-ps2-stuff.27431/

### Firmware 1.06 for DESR-5000 & DESR-7000
1. Download 1.06_LITE.7z
2. Extract everything (on USB)
3. Run HDDTOOL.ELF
4. When the XMB shows up, recreate the DVR area in the System Settings with the option that repartitions/formats the HDD

### Firmware 2.11 for DESR-5500 up to DESR-7700
1. Download 211_for_repart.7z.001 & 211_for_repart.7z.002 (splitted in 2 parts because of GitHub upload limit)
2. Extract everything (on USB)
3. Run HDDTOOL.ELF
4. Run BOOT-XFW_20191121_927fd4a.elf
5. Copy bootflag.txt to xfrom:/BIEXEC-SYSTEM/, so the system software recreates DVR partitions and copies default files on them

Files & usage guide provided by krHACKen (aka kHn).