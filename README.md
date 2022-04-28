**0.7.0 Big Sur**
- Bugs
> Trackpad (touch to click not working but it can use by press right/left on the trackpad).
> Brightness key not working.
> First boot may stuck (add "-v" in boot-arg may fix).
- More info:
> Pickermode is "Builtin" (not a bug).
> Use Horndis kext (you can google to know more)

**0.8.0 Big Sur**
- Bugs
> Trackpad (touch to click not working but it can use by press right/left on the trackpad).
- Changes
> Add Brightnesskey kext to fix brightness function key.
> Add "-v" to boot-arg.
> Use pickermode is External (follow opencore guide) to enable GUI on bootloader.

**0.8.0 Monterey**
- Bugs
> Same as Big Sur.
> Sometime it occured backlight error while boot (you MUST force restart)
- Changes
> Add BlueToolFixUp kext to fix bootloop.
> Change some settings in config.plist to avoid bugs in Monterey
> Use SSDTTime to make custom SSDT
> Change pickermode themes to Mordern
> Mostly fix disk1s5, apfs, applekeystore error.
> Turn off "-v", no command line exist while booting

- WARNING! DO NOT USE 0.X BIGSUR EFI FOR MONTEREY (Monterey have some changes that will make old versions cant boot)
