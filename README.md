# Dynamic System Tweaks Magisk Module for arm64-v8a devices

### Version:
v1.3

### Last Updated:
02/04/25

## Description
This improves overall System performance without overheating and losing battery power.

## Installation 
1. Flash the module in Magisk
3. Reboot
4. Enjoy!

## Requirements:
- Magisk 20.4 or higher
- Android 10 or higher
- Rooted device

## Changelog
[View changelog here](https://github.com/PS2ClassicsVault/DynamicSystemTweaks-arm64-Magisk-Module/blob/main/changelog.md)

## Requirements:
- CPU with 8 cores (needed for dex2oat to perform 8 thread tasks).
- arm64-v8a device only

This version works similar to our original DynamicSystemTweaks Module, but is only intended for 64-bit only devices, running this on a non-64-Bit device will cause your system to bootloop!


## Warnings:
This module will run your dalvik VM via your device in x64-bit mode this will allow applications to run more efficiently but may also use a bit more memory depending on your device usage. When you install this module please allow 30 mins to recompile before makind any decisions if this module is worth your time as any changes to dalvik.can take up to 30mins to complete before you see any results.

In case if an emergency such as a bootloop upon installing this module, please be sure to install a anti bootloop module that can assist in recovering your system by disabling all magisk modules, if this happens this is not the module itself but your system either doesn't meet our requirements or the module caused instabilities that caused this issue!

Not all devices run the same this should be treated the same as well since  not all devices will react the same as you expect! 