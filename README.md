> [!WARNING]
> I'm not responsible nor give a warranty for bricking/losing your data as they're no a "**SAFE**" word in firmware mod world.
> 
> This repo was mainly for those that understanding what they're doing, It's not same thing like messing around with driver that you can easily revert it back, **IF YOU'RE DOING IT WRONG WHILE TRANSFERRING YOUR DATA TO THE MOD IMAGE NOR WHILE FLASHING THE BIOS, YOU WILL END UP WITH DEATH DEVICE UNTIL RECOVERY IT USING FLASHPROG**.
>
> Before flashing the BIOS you must transfer all of your data first (MAC,UUID, WinKey, etc.), Otherwise you will lose it or having problem with LAN and RGB keyboard function
>  
> **-- YOU HAVE BEEN WARNED --**

> [!IMPORTANT]
> You can't flash the BIOS from this repo the sameway using official vendor method, either you will be to use **Flash Programming Tool (FPT) "INTEL"** or **Flash Programmer (FP) "INTEL/AMD"**.
> 
> This repo does not cover how to transfer data, as each device has a different approach. It also does not cover recovering bricked devices. Search for this information yourself.

***

## OEMCustomBios
This project focuses on the latest updates to BIOS components (depending on the date the mod was made), disabling flash protection, adding new features, and unlocking hidden menus.

> [!TIP]
> Both of this tool requires administrator permission
> 
> Disable BIOS LOCK and FPRR LOCK using GRUBMOD or RU.EFI before flashing the BIOS mod.

### INTEL Flash Programming Tool (FPT)
 - *Backup*
   - FPTW -d Backup_FP.rom
   - FPTW -bios -d Backup_FPT.rom
 - *Flash*
   - FPTW -bios -f FPT.rom

### MEInfo
 - *Command*
   - MEInfo -verbose

### Related GUIDE
  - MODGRUB/RU.EFI use case : https://github.com/dreamwhite/bios-extraction-guide
  - CH341A (FP) : https://winraid.level1techs.com/t/guide-using-ch341a-based-programmer-to-flash-spi-eeprom/30834
  
### Related Tool 
 - UEFITool NE : https://github.com/LongSoft/UEFITool
 - UEFITool v25 : https://github.com/LongSoft/UEFITool/releases/tag/0.25.0
 - IFR Extractor : https://github.com/LongSoft/Universal-IFR-Extractor
 - GRUBMOD : https://github.com/datasone/grub-mod-setup_var
 - HxD : https://mh-nexus.de/en/hxd/

***

> [!NOTE]
> Keep in mind this is unpaid work, so don’t expect me to respond to requests quickly. I’ll only handle some, depending on the device.
