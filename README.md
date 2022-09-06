
# Dell Latitude E5430 OpenCore EFI Big Sur
OpenCore EFI for Dell Latitude E5430 **(vPro, i5-3380m)**

**Tested on Mac OS Big Sur**, Fully working + iServices.

This was my first time ever making an EFI, with lots of errors and unused entries.

Take this repository as an example to follow, but *I would not personally recommend using this as is.*

Disclaimer: I'm not responsible for any damage you may cause, use this at your own risk (I Strongly recommend making your own EFI).

---

| My Specs:                                      |
|---------------------------------------------|
| Intel Core i5-3380m @ 2.6GHz / 3.9Ghz Turbo | 
| Intel HD 4000 Graphics                      |
| 4GB Ram (DDR3 1600 MHz)                     |
| 500GB SATA Disk (WD Black)                  |
| 1366x768 14 inches                          |
| Intel 7260 HMW Dual-Band                    |


# How to use this?

After you've followed the guide on [how to make the installation media](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/), just download the folder in this repository, and copy it in the main directory of your installation media.

A Correctly formatted media, should contain *two folders* in its root:
- **"com.apple.recovery.boot"** - with the Mac OS "BaseSystem" or "RecoveryImage" file(s).
- **"EFI"** - The one you've downloaded from here.

If You want to also use iServices, you'll need to modify the "config.plist" file, located in EFI>OC>"config.plist", using the ["ProperTree"](https://github.com/corpnewt/ProperTree) editor.

After you've opened the file using ["ProperTree"](https://github.com/corpnewt/ProperTree), follow the  [dortania's guide](https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/ivy-bridge.html#platforminfo) on how to use [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) and apply modifications.
___




## Tools I Used:
- [ProperTree](https://github.com/corpnewt/ProperTree)
- [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
