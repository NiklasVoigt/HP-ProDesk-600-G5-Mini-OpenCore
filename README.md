# HP-ProDesk-600-G5-Mini-OpenCore

Repository to hold the files needed to install and run macOS on HP ProDesk 600 G5 mini

## Tested versions
OpenCore: 0.8.8
MacOS: macOS Ventura 13.2

## Configuration information
Key | Value
--- | ---
CPU | Intel Core i3 9100T @ 3.1GHz
iGPU | Intel Graphics UHD 630
RAM | DDR4 2400MHz 8GB
SSD | NVMe WD PC SN520 256GB
Audio | Conexant CX20632 Audio Codec
Wireless | BCM94352Zz (Dell DW1560)

## Working
- nearly all

## Not Working
-

## Important for BCM94352Zz
Add the right Kexts, AirportBrcmFix => BlueToolFixup => BrcmFirmwareData => BrcmPatchRAM3, in this specific order. Make sure to turn off the plugin AirPortBrcm4360_Injector (false) . No boot arg needed.

## Thanks
-Apple
-[@Acidanthera](https://github.com/acidanthera)
-[deeveedee](https://www.insanelymac.com/forum/topic/343937-guide-catalina-big-sur-monterey-ventura-on-hp-elitedesk-800-g4g5-mini-the-perfect-macmini81-hackintosh/)
