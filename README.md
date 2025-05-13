# Large Heap Fix Magisk Module

## Descriptions
- Fixes force closes in apps which using largeHeap="true" (like game apps and music/video streaming apps) caused by too low dalvik.vm.heapsize settings.
- Sets dalvik.vm.heapsize to 512m. You can check in Termux/Terminal `su -c getprop dalvik.vm.heapsize`. If the default value is lower than 512m, then you may need this module.

## Requirements
- Magisk/KernelSU/Apatch/Kitsune Mask installed

## Installation Guide & Download Link
- Install this module https://www.pling.com/p/2279229/ via Magisk app or KernelSU app or Recovery if Magisk installed
- Reboot

## Support & Bug Report
- https://t.me/ryukinotes/54
- If you don't do above, issues will be closed immediately

## Credits and Contributors
- https://t.me/androidryukimodsdiscussions
- You can contribute ideas about this Magisk Module here: https://t.me/androidappsportdevelopment

## Sponsors
- https://t.me/ryukinotes/25


