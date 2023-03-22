![OFRP](https://image.ibb.co/cTMWux/logo.jpg "OFRP")

OrangeFox Recovery Project (OFRP) R11.1 for Redmi K40/Mi 11X/POCO F3 (alioth)
======================================

# How to build
Download OFRP's source and alioth's repos. Your local manifest should be something like:

```bash
<?xml version="1.0" encoding="UTF-8"?>
<manifest>

<!-- Device tree -->
  <project name="masemoel/device_xiaomi_alioth_recovery" path="device/xiaomi/alioth" remote="github" revision="fox_12.1"/>
</manifest>
```

Then go to the source folder and run:

```bash
. build/envsetup.sh && lunch twrp_alioth-eng && make adbd bootimage
```

# Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU | Octa-core (1x 3.2GHz Kryo 585 + 3x 2.42GHz Kryo 585 + 4x 1.8GHz Kryo 585)
Chipset | Qualcomm SM8250-AC Snapdragon 870
GPU | Adreno 650
Memory | 6/8 GB
Shipped Android Version | Android 11 with MIUI 12 for POCO
Storage | 128/256 GB
Battery | 4520 mAh (non-removable)
SIM Slots | Dual Nano SIM card capability
Dimensions | 163.7 x 76.4 x 7.8 mm
Display | 2400x1080 pixels, 6.67 (~386 PPI), 20:9 ratio, 120hz, HDR10
Rear Camera | 48 MP + 8MP + 5MP
Front Camera | 20 MP
Release | 2021, January
NFC	| Yes
USB	| C-type 2.0 with fast charge up to 33 W, OTG
Sensors | Fingerprint ID with the power button, infrared

![Redmi K40](https://img.gkbcdn.com/s3/p/2021-02-26/Xiaomi-Redmi-K40-Pro-8GB-128GB-White-454784-0.jpg "Redmi K40")
