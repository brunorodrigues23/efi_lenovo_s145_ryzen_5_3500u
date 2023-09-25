# OpenCore EFI for AMD Laptops

**OpenCore version: 0.7.5**

**macOS: Ventura**


## My laptop is **Lenovo S145**
- CPU model: AMD RAMD Ryzen 5 3500U with Radeon (TM) Vega Graphics
- GPU model: Radeon (TM) Vega 8 Graphics
- SSD: XPG S41 TUF 512gb 
- Memory ram: 12gb DDR4
- Wifi/Bluetooth model: Intel AX200NGW


## Preparing
- Please change MLB/ROM/Serial Number/UUID by using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
- Remember to install MacOS with WhateverGreen and after installation switch to Nootedred (It's in UTILS/APU ACTIVATION)

**NVRAM**  
- boot-args: `-v keepsyms=1 debug=0x100 npci=0x2000 vsmcgen=1`  
- add `alcid=xx` replace `xx` with your layout-id 
- add `agdpmod=pikera` if you got black screen after boot



### What is working?
- APU Nootedred
- Audio / p2
- Wi-fi
- HDMI
- Trackpad
- keyboard
- 

### What is not working? (I will be solving it soon)
- USB (So far, it works randomly)
- Bluetooth
- Brightness Key

## Image Model laptop
![A SwiftUI App](https://www.lenovo.com/medias/Notebook-S145-Linux-1.png?context=bWFzdGVyfHJvb3R8NzEzNzB8aW1hZ2UvcG5nfGgzOS9oMGEvMTA2MzkzNjIzOTIwOTQucG5nfDQwNTMwNTJlMGE5ZWExY2Q2ZWMyNDgxYWUzMDBlN2JjOTYyZWExNzAyMGRlYzFlYmZhMTJlMjc5YjdjNGZiMzk)