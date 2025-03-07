# ASUS-FX504GD-Opencore
(my config of opencore to get macOS to boot on FX504 Laptop model)
- Important Notes:
This Repo will not be maintain for normal user anymore
Due to My laptop screen broke off , I repurpose it as a mini PC
The config will be for HDMI main display & smbios is Macmini8,1

<p align="left">
    <a href="https://github.com/pnapt/ASUS-FX504GD-Opencore/releases">
        <img src="https://img.shields.io/badge/Latest%20Release-0.8.1-green" /></a>
    <a href="https://github.com/pnapt/ASUS-FX504GD-Opencore/releases">
        <img src="https://img.shields.io/badge/Latest%20Build-Download-green" /></a>
    <a href="https://github.com/pnapt/ASUS-FX504GD-Opencore/blob/main/OpenCore/README.md">
        <img src="https://img.shields.io/badge/Read-Info--Guide-red" /></a>
    <a href="https://github.com/pnapt/ASUS-FX504GD-Opencore/blob/main/OpenCore/ConfigExplain.md">
        <img src="https://img.shields.io/badge/How--To-Config-blue" /></a>

# How-to guide

[Here](OpenCore/README.md)

# Info
> Old Repository
    https://github.com/pnapt/FX504-Build-OC

__Notes__
- Opencore EFI on HDD & Install macOS on ssd
- Windows EFI on SSD & Install windows on ssd

__My laptop issue__
- Maybe HDMI

<img src="https://github.com/pnapt/ASUS-FX504GD-Opencore/blob/main/FX504-AboutThisMac.png"/>


# Info
**Laptop Specs**
| Hardware | Details |
|------------|-------------------------------|
| Model | ASUS FX504GD |
| BIOS Ver | 322 |
| Processor | Intel Core i5 8300H |
| Memory | 2x8GB DDR4 2666MHz |
| iGPU | Intel UHD Graphics 630 |
| dGPU | NVIDIA GeForce GTX 1050 |
| Wifi | Intel Wireless-AC 9560 |
| Trackpad | ELAN 1200 |
| Sound | Realtek ALC255 |
| M.2 Nvme | WD Black SN750 500 GB |
| HDD 2.5 | ST1000LM035-1RK172 1TB  |

**OS**
| OS | Details |
|--------------|-----------------|
| macOS | Monterey 12.2 (21D49)|
| Dual boot OS | Windows 11 21H2 |


**What's Works**
- [x] Intel UHD Graphics 630
- [x] Wifi
- [x] Bluetooth 
- [x] Ethernet(LAN) 
- [x] Build-in Keyboard
- [x] Trackpad+Gestures
- [x] Screen brightness + fnkeys
- [x] Audio (Speaker + Internal Mic & Headphone + External Mic) 
- [x] All USB Port (Usb Mapped)
- [x] M.2 NVME + 2.5" HDD
- [x] Battery status
- [x] Sleep/Wake
- [x] Shutdown

**Can't Tests**
- [ ] HDMI (It's works but not that fine)

**Not work**
- [ ] dGPU (of course apple have ended support)
    maybe will try to Build an implement ver. form OC legacy patcher

## Opencore Config Guide

[Here](OpenCore/README.md)

# Benchmark Info

[Here](OpenCore/BenchmarkInfo.md)

# Credit
__People who made opencore project and kext__
- https://github.com/acidanthera/ for Opencore

- https://github.com/corpnewt for all tools eg.ProperTree ,USB Map ,GenSMBIOS and more.

- https://github.com/hackintosh-stuff/ComboJack for Combojack 3.5 fix

__Previous People who build EFI for this laptop__
- **Special Thanks to**
    - https://github.com/PoomSmart for guide fx504 
    Repo:https://github.com/PoomSmart/ASUS-FX504GE-Hackintosh
- And 
    - https://github.com/wilsomwong
    Repo:https://github.com/wilsomwong/Asus-TUF-FX504GE-Hackintosh

    - https://github.com/RobyRew
    Repo:https://github.com/RobyRew/ASUS-FX504GE-Hackintosh_OpenCore

    - https://github.com/MegaStood
    Repo:https://github.com/MegaStood/Hackintosh-FX504GE-ES72

    - https://github.com/dongcodebmt for way to fix combojack alc 255
    Repo:https://github.com/dongcodebmt/VX5-591G-OpenCore

- r/hackintosh Community https://www.reddit.com/r/hackintosh/ 
