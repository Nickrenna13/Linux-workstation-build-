# BIOS Issues & Fixes

## Boot Loop After First Power-On
- Cause: Incorrect memory profile
- Fix: Disabled XMP/EXPO and manually set RAM timings

## NVMe Not Detected
- Cause: BIOS storage mode set incorrectly
- Fix: Switched from RAID to AHCI

## GPU Not Initializing
- Cause: PCIe slot set to auto
- Fix: Forced PCIe Gen4 mode

## Installing Newer Bios 
- Cause: Small issues with components (Keyboard, mouse) and motherboard wifi issues.  
- Fix: Flash new Bios on flash drive and install new bios on PC

## Lessons
BIOS issues often come down to defaults that don't match the hardware. 
Small changes can fix major problems.
If you update your bios from one version no a newer version, sometimes you can not go back to older versions of bios. 
