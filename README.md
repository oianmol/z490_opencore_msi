# z490_opencore_msi
OpenCore 1.0.8 EFI for MSI MPG Z490 Gaming Plus (MS-7C75) · i7-10700 · UHD 630 · SMBIOS iMac20,1

| Component | Version |
|---|---|
| OpenCore | 1.0.8 |
| Lilu | 1.7.2 |
| WhateverGreen | 1.7.1 |
| AppleALC | 1.9.8 (layout-id 3) |
| VirtualSMC / SMCProcessor / SMCSuperIO | 1.3.8 |
| LucyRTL8125Ethernet | 1.2.4 (present, disabled in config) |
| USBMap | custom port map |

**Display:** BenQ MA270UP (27" 4K) on the board's HDMI port. The Z490 Gaming Plus HDMI output is HDMI 1.4, so expect 2560x1440@60 (or 4K@30); 4K@60 needs the DisplayPort output and connector patches changed from HDMI (`0x800`) to DP (`0x400`). OpenCore picker scaling is automatic (`UEFI > Output > UIScale = 0`).

**Before booting:** `PlatformInfo > Generic` has `MLB`, `SystemSerialNumber` and `SystemUUID` blanked. Generate your own with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) for iMac20,1.

![About this Hackintosh](Screenshot%202020-11-01%20at%203.01.27%20PM.png)
