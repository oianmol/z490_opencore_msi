# z490_opencore_msi
OpenCore 0.9.4 EFI for MSI MPG Z490 Gaming Plus (MS-7C75) · i7-10700 · UHD 630 · SMBIOS iMac20,1

| Component | Version |
|---|---|
| OpenCore | 0.9.4 |
| Lilu | 1.5.2 |
| WhateverGreen | 1.4.9 |
| AppleALC | 1.5.9 (layout-id 3) |
| VirtualSMC / SMCProcessor / SMCSuperIO | 1.2.2 |
| LucyRTL8125Ethernet | 1.0.0d6 (present, disabled in config) |
| USBMap | custom port map |

**Before booting:** `PlatformInfo > Generic` has `MLB`, `SystemSerialNumber` and `SystemUUID` blanked. Generate your own with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS) for iMac20,1.

![About this Hackintosh](Screenshot%202020-11-01%20at%203.01.27%20PM.png)
