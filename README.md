# omni_ONA19TB002

About Device
 This is for Onn 8" tablet from walmart
 
CPU 1.3GHz quad core processor RAM Included 2GB RAM Upgradeable Storage Drive Size 16GB Storage Drive Type Display Size 8 Display Resolution 1280 x 800 Graphics Chip Graphics Memory Wi-Fi 802.11a/b/g/n Has Bluetooth Yes OS Android 9 Camera Resolution 2 MP Front-Facing Camera Resolution 0.3 Ports 3.5mm audio jack Ports microUSB USB Ports 1 Card Readers Micro-SD Card Reader Size Warranty / Support Size 8.2 x 4.8 x 0.4 inches thick Weight 12.2 ounces Company Website https://www.walmart.com/ip/Onn-Android-Tablet-8-16GB-Storage-Bonus-20-off-Walmart-eBooks-Included/767511102

This device tree can be used to build twrp for Onn 8" Walmart Tablet


Build Instructions

export ALLOW_MISSING_DEPENDENCIES=true
source build/envsetup.sh
lunch omni_ONA19TB002
mka recoveryimage
