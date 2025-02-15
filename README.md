#### NUC8I7BEH Hackintosh with OpenCore 0.6.7 Final UEFI
##### Mac Big Sur 11.2.1
![AboutThisMac](./image/20210226-222617@2x.png)
### Supported macOS versions
+ macOS Mojave 10.14.6
+ macOS Catalina 10.15.7
+ macOS Big Sur 11.x

### BIOS Setting
##### BIOS version: [0087](https://raw.githubusercontent.com/farboys/NUC8I7BEH/main/BIOS/BE0087.bio)
+ Disable
    - Legacy Boot
    - Fast Boot
    - Network Boot
    - Secure Boot
    - Inter VT for directed I/VO(VT-d)
+ Enable
    - Boot USB Devices First
    - Boot Network Devices Last
+ Wake on LAN from S4/S5
    - Stay Off
+ Devices Settings
    - Video IGD Minimum Memory       [64 MB]
    - Video IGD Aperture Size        [256 MB]
    - Video IGD Primary Video Port   [HDMI or Thunderbolt, you choose]
    - Video IGD Secondary Video Port [None]
    - Onboard Devices WLAN           [Disable]
    - Onboard Devices Bluetooth      [Disable]

### Not works
+ Card reader
+ IR receiver
+ You tell me

### How to install
+ Create bootable USB with macOS Catalina (Windows or Mac)
+ Copy /EFI to your BOOT folder
+ Change your mac serial number in /EFI/OC/config.plist

### Spec
+ WLAN+Bluetooth
    - Apple BCM943602CS
    - BCM943602CS PCIe M.2 NGFF
    - WIFI Antenna
+ Memory
    - ADATA 16GB DDR4 2666 x2
+ SSD
    - SAMSUNG 860 EVO 250GB (MZ-76E250B)
+ Monitor1
    - Dell U2720Q (Thunderbolt3 to DP)
+ Monitor2
    - Dell P2414H (Native HDMI)
