# Dell XPS-8940 OpenCore

![Alt text](/screenshot.jpg?raw=true "Screenshot")

Dell XPS 8940 - OpenCore
OpenCore 0.8.6 - MacOS Monterey 12.6.1 - BIOS version 2.10.0

Shutdown/Reboot/Sleep works without any issue.

PLEASE GENERATE YOUR OWN SMBIOS deets (SN/MLB/UUID/ROM)

(use genSMBIOS with iMac19,1 https://github.com/corpnewt/GenSMBIOS)

System: Dell XPS 8940

CPU: Intel i7-10700

RAM: 4x8GB DDR4-2666, 32GB

SSD:WD_BLACK SN770 NVMe SSD 

GPU: NONE

iGPU: UHD 630 (enabled)
VDA Decoder: Fully Supported

AirPort/WiFi: Working

Audio: Realtek ALC3861 (actually RealtekRTL8111)


--

USB Mapped for all front USB ports + all USB3.0 ports on the back

--

BIOS v2.10.0

change to AHCI instead of RAID
Disable the graphics card automatic mode and use the Intel HD630

Note: The original Micron SSD cannot be installed and used, please replace the SSD!!
