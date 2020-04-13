# vold-exfat

The repository is the fork of https://android.googlesource.com/platform/system/vold/ modified for special needs.

This `vold` daemon uses exFAT mount for external usb storage. As the consequence it doesn't support fsck and formatting.

- Compatibility: Android 5.1 Lollipop
- Module: vold
- Tested with: Amazon FireTV (tank), Fire OS 5.2.7.2

## how-to

Replace your `system/vold` with the current project, build normally.
