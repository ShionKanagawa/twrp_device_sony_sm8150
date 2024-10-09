# TWRP device tree for Xperia 1

Xperia 1 (codenamed _"griffin"_) is a high-end smartphone from Sony.

It was announced & released on February 2019.

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
SoC     | Snapdragon® 855 (SM8150)
CPU     | 1x2.84 GHz Cortex-A76 & 3x2.42 GHz Cortex-A76 & 4x1.8 GHz Cortex-A55
GPU     | Adreno 640
Memory  | 6 GB RAM
Shipped Android Version | 9.0
Storage | 64/128 GB
Battery | Li-Ion 3300 mAh, non-removable, graphene-enhanced
Display | 1644 x 3840 pixels, 21:9 ratio (~642 ppi density), 6.50 inches, OLED, 60Hz, Dolby Vision, HDR10+

## Device picture

![Xperia 1](https://www.sony.com.hk/image/5eb042f99b9b7307f2d447527fdd83a2?fmt=pjpeg&wid=4000&qlt=43)

## Features

Works:

- [X] ADB
- [X] Decryption
- [X] Display
- [X] Fasbootd
- [X] Flashing
- [X] MTP
- [X] Sideload
- [X] USB OTG
- [X] Vibrator

## To use it:

```
fastboot --disable-verity --disable-verification flash vbmeta vbmeta.img
fastboot flash boot boot.img
```
