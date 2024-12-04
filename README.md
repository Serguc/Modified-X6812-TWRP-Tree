#  Recovery tree of  Infinix Hot 11S

It was announced & released on November 2023.

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
SoC     | MediaTek Helio G88 (MT6768) (6nm)
CPU     | Octa-core (2x2.2 GHz Cortex-A76 & 6x2.0 GHz Cortex-A55)
GPU     | Mali-G52 MC2
Memory  | 8 GB RAM
Shipped Android Version | Android 11 XOS Dolphin v7.6.0
Storage | 64/128 GB
Battery | Li-Po 5000 mAh, non-removable
Display | 6.78-inch, 1080*2460 FHD+ Resolution; Dynamic 180Hz Refresh Rate
Camera  | 64 MP (Samsung® ISOCELL GW3) and 13 MP (Samsung® ISOCELL 3L6)

## Device picture

![1]()


## Features

Works:

# Building
```bash
source build/envsetup.sh
lunch twrp_shark8-eng
mka bootimage
```

## To use it:

```
fastboot flash boot out/target/product/ X6812/boot.img
```
