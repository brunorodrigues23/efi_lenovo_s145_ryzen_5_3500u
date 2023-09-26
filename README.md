# OpenCore EFI for AMD Laptops

**OpenCore version: 0.7.5**
**macOS: Ventura**

## My laptop is **Lenovo S145 15API**
- CPU model: AMD RAMD Ryzen 5 3500U with Radeon (TM) Vega Graphics
- GPU model: Radeon (TM) Vega 8 Graphics
- SSD: XPG S41 TUF 512gb 
- Memory: 12gb DDR4
- Wifi/Bluetooth model: Intel AX200NGW

## Preparing
- In Bios, leave secureboot as disabled.
- Please change MLB/ROM/Serial Number/UUID by using [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
- Remember to install MacOS with WhateverGreen and after installation switch to Nootedred (It's in UTILS/APU ACTIVATION)


### What is working?
- APU Nooted Red
- Speaker / Audio P2
- Wi-fi / Bluetooth
- HDMI
- Trackpad
- Keyboard

### What is not working? (I will be solving it soon)
- USB (So far, it works randomly)
- Brightness Key
- Microphone internal
- Camera internal


## Image Model laptop
![A SwiftUI App](https://www.lenovo.com/medias/Notebook-S145-Linux-1.png?context=bWFzdGVyfHJvb3R8NzEzNzB8aW1hZ2UvcG5nfGgzOS9oMGEvMTA2MzkzNjIzOTIwOTQucG5nfDQwNTMwNTJlMGE5ZWExY2Q2ZWMyNDgxYWUzMDBlN2JjOTYyZWExNzAyMGRlYzFlYmZhMTJlMjc5YjdjNGZiMzk)