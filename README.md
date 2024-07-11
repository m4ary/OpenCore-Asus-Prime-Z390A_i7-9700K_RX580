
# Hackintosh Build with ASUS Prime Z390-A and i7-9700K

![System Info](https://github.com/m4ary/OpenCore-Asus-Prime-Z390A_i7-9700K_RX580/blob/main/screenshot-macos13.jpg?raw=true)

## Important Notice
**Do not sign in with your Apple ID until you change the platform information using [this tutorial](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#platforminfo).**

## Summary
This build has been tested with the following macOS versions:
- macOS Ventura 13.6.7
- macOS Ventura 13
- macOS Monterey 12.0.1
- macOS Big Sur 11.3
- macOS Catalina 11 Beta
- macOS Catalina 10.15.2
- macOS Mojave 10.14.6

### Working Features
1. AirDrop / Handoff
2. FaceTime / iMessage


### Not Working Features
1. **DRM (Direct Rendering Manager):** DRM is not working, which means Apple TV+ is not functional. Use Chrome for Netflix. You can try to fix it using [this link](https://dortania.github.io/OpenCore-Post-Install/universal/drm.html).

2. Sleep

## Components
- **Motherboard**: ASUS PRIME Z390-A
- **CPU**: Intel® Core™ i7-9700 Processor
- **iGPU**: Intel® UHD Graphics 630
- **dGPU**: SAPPHIRE PULSE Radeon RX 580 8GB GDDR5
- **LAN**: Intel® I219V, 1 x Gigabit LAN Controller
- **WiFi/Bluetooth**: BCM943602CS
- **Audio**: Realtek® ALC S1220A 8-Channel High Definition Audio
- **Storage**: Samsung SSD 970 EVO Plus 500GB

## Modifications and Fixes

1. **Installation Stuck on Samsung 970 EVO PLUS**:
   - Update the firmware for the Samsung 970 EVO PLUS from [here](https://www.samsung.com/semiconductor/minisite/ssd/download/tools/).
   - Write the updated firmware on a USB drive and boot from it.