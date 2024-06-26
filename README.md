# Asus-K550J-Hackintosh
 Asus-K550J-Hackintosh EFI Opencore

This repository is about hackintosh on **Asus-K550J**. For now, all the hardware is working as expected, it's ready for daily usage and I will continue to follow the updates of OpenCore and macOS.

Anyone who has the same board can use my EFI directly. The source EFI folder uses debug version of OpenCore, mainly used for installation and testing. It’s recommended to use the release version for daily usage, you can replace it yourself or just download my release. Either way, don’t forget to edit the `EFI/OC/config.plist` file, you should generate your own SMBIOS info by following the [Haswell Config Guide #PlatformInfo](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html#platforminfo). 

Highly recommended reading the whole [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/) before you start.

## Hardware

* Motherboard: Asus K550J
    * Ethernet: Realtek RTL8168/8111
    * Wi-Fi/BT: Broadcom BCM94360HMB 802.11ac(Mini PCIE Adapter)
    * Audio: Conexant CX20751/2 (layout-id: 3)
* CPU: Intel Core i7-4720HQ, 3500 MHz
* iGPU: Intel HD Graphics 4600
* eGPU: GeForce GTX 950M (disable)
* RAM: DDR3L 1600 8GB

## Software

* Bootloader: OpenCore 1.0.0
* OS: macOS Sonoma 14.5 (MacBookPro 14,1)


## Thanks

 Sonoma Install Guide [GeekyCoder7/OpenCore-EFI-Lenovo-Y50-70](https://github.com/GeekyCoder7/OpenCore-EFI-Lenovo-Y50-70/) 
 