#  Recovery tree of  Infinix Hot 11S

It was announced & released on November 2023.

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
SoC     | MediaTek Helio G88 (MT6769) (12nm)
CPU     | Octa-core (2x2.0 GHz Cortex-A75 & 6x1.8 GHz Cortex-A55)
GPU     | Mali-G52 MC2
Memory  | 4/6 GB RAM
Shipped Android Version | Android 11 XOS Dolphin v7.6.0
Storage | 64/128 GB
Battery | Li-Po 5000 mAh, non-removable
Display | 6.78-inch, 1080*2460 FHD+ Resolution; Dynamic 90Hz Refresh Rate
Camera  | 50 MP (main) and 8 MP (frontal)

## Device picture

![1]()


## Features

Works:

# Building
```bash
source build/envsetup.sh
lunch twrp_X6812-eng
mka bootimage
```

## To use it:

```
fastboot flash boot out/target/product/ X6812/boot.img
```
