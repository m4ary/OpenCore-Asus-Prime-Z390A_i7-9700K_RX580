# Hackintosh build with ASUS Prime Z390-A and i7-9700K
![system_info](https://github.com/m4ary/OpenCore-Asus-Prime-Z390A_i7-9700K_RX580/blob/main/screenshot-macos13.jpg?raw=true)



## READ BELOW BEFORE USE
1- Don't sign in with your Apple ID until changing the platforminfo using [this](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#platforminfo) tutorial.



## Summary
this build is tested with:
- macOS Ventura 13
- macOS Monterey 12.0.1
- MacOS BigSur 11.3
- MacOS Catalina 11 Beta
- MacOS Catalina 10.15.2
- MacOS Mojave 10.14.6

working:
1. AirDrop \\ Handoff
2. FaceTime \\ iMessage
3. Sleep

not working:
1. DRM (Direct Rendering Manager):
DRM is not working which means Apple TV+ is not wokring and using chrome for netflix, you can try fix it using this [link](https://dortania.github.io/OpenCore-Post-Install/universal/drm.html)



## Components
- M/B: ASUS PRIME Z390-A
- CPU: Intel® Core™ i7-9700 Processor
- iGPU: Intel® UHD Graphics 630
- dGPU: SAPPHIRE PULSE Radeon RX 580 8GB GDDR5
- Lan: Intel® I219V, 1 x Gigabit LAN Controller
- WiFi/Bluetooth: BCM943602CS
- Audio: Realtek® ALC S1220A 8-Channel High Definition Audio
- Storage: Samsung SSD 970 EVO Plus 500GB


## Modification and fixes

1. installation stuck when choose **Samsunge 970 EVO PLUS** as main Storage
updating the firmware drive system for the Samsunge 970 EVO PLUS from  [here](https://www.samsung.com/semiconductor/minisite/ssd/download/tools/) and Write it on the USB drive and boot from it
