# Large Heap Fix Magisk Module

## Descriptions
- Fixes force closes in apps which using largeHeap="true" (like game apps and music/video streaming apps) caused by too low dalvik.vm.heapsize settings.
- Sets dalvik.vm.heapsize to 512m. You can check in Termux/Terminal `su -c getprop dalvik.vm.heapsize`. If the default value is lower than 512m, then you may need this module.

## Changelog

v0.3
- Resets module folder/files permissions at post-fs-data

v0.2
- Does not change dalvik.vm.heapgrowthlimit because it's too much of a burden on RAM

v0.1
- Initial release

## Requirements
Magisk/KernelSU/Apatch/Kitsune Mask installed

## Installation Guide & Download Link
- Install this module https://bicolink.com/m73R2IWC via Magisk app or Kitsune Mask app or KernelSU app or Apatch app or Recovery if Magisk or Kitsune Mask installed
- Reboot

## Download Tutorial
https://t.me/ryukinotes/97

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- https://t.me/androidryukimodsdiscussions
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Sponsors
https://t.me/ryukinotes/25


