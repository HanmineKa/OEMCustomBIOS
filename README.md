<h1 align="center">OEMCustomBIOS</h1>

<div align="center">
 
[![ubu](https://img.shields.io/badge/UEFI%20BIOS%20Updater-001f3f)](https://winraid.level1techs.com/t/tool-guide-news-uefi-bios-updater-ubu/30357)
[![rebaruefi](https://img.shields.io/badge/github-ReBarUEFI-800000?logo=github)](https://github.com/xCuri0/ReBarUEFI)
[![NvStrapsRebar](https://img.shields.io/badge/github-NvStrapsReBar-06470C?logo=github)](https://github.com/terminatorul/NvStrapsReBar)
[![device](https://img.shields.io/badge/Device-List-00BFFF)](https://github.com/HanmineKa/OEMCustomBIOS/blob/main/Device.md)
 
This project focuses on the latest updates to BIOS components (depending on the date the mod was made), disabling flash protection, adding new features Resizable Bar from ReBarUEFI/NvStrapsRebar, and unlocking hidden menus.

</div>

***

> [!WARNING]
> I'm not responsible nor give a warranty for bricking/losing your data as they're no a "**SAFE**" word in firmware mod world.
> 
> This repository is mainly intended for those who understand what they are doing. It’s not the same as messing around with a driver that you can easily revert. **IF YOU MAKE A MISTAKE WHILE TRANSFERRING YOUR DATA TO THE MOD IMAGE OR WHILE FLASHING THE BIOS, YOU MAY END UP WITH A DEAD DEVICE UNTIL YOU RECOVER IT USING FLASHPROG**.
>
> Before flashing the BIOS you must transfer all of your data first (MAC,UUID, WinKey, etc.), Otherwise you will lose it or having problem with LAN, etc.
>  
> **-- YOU HAVE BEEN WARNED --**

> [!IMPORTANT]
> You can't flash the BIOS from this repo the sameway using official vendor method, either you will be to use **Flash Programming Tool (FPT) "INTEL"** or **Flash Programmer (FP) "INTEL/AMD"** or **BIOS FlashBack or similiar**.
> 
> This repo does not cover how to transfer data, as each device has a different approach. It also does not cover recovering bricked devices. Search for this information yourself.

> [!TIP]
> Both FPT and MEInfo/TXEInfo requires administrator permission.
> 
> Make sure the BIOS currently installed is the same version as the mod, to avoid an EC version mismatch.
> 
> Disable BIOS Lock and FPRR Lock using GRUBMOD or RU.EFI before flashing the BIOS mod.
>
> If FPT still encounters error 167, it means the device is configured with FLOCKDN. In this case, only the FP method can be used.
> 
> Disable Device Encryption/BitLocker.

***

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
