# EFI-GIGABYTE-A520i-OpenCore-Hackintosh

### OpenCore

[OpenCore 1.0.1](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Sequoia 15.0 

### Hardware

- Motherboard: gigabyte A520i dash
- CPU: AMD Ryzen 5 5600G
- GPU: AMD Radeon Vega 7 (iGPU)
- Audio: Realtek ALC897
- Ethernet: Realtek RTL8111(G) Family Controller

#### PS:
 - All USB ports are customized well.
 - Wireless Connection & Bluetouch don't be customized.
 - Audio cannot be drivered.

### Bios Setup

| Name | Option |
| ----- | --- |
|BIOS Features->CSM Support|Disabled|
|BIOS Features->Secure Boot->Secure Boot|Disabled|
|Peripherals->USB Configuration->XHCI Hand-off|Enabled|
|Peripherals->USB Configuration->EHCI Hand-off|Enabled|
|Peripherals->Super IO Configuration->Serial Port 1|Disabled|
|Peripherals->Super IO Configuration->Serial Port 2|Disabled|
|Peripherals->Serial Port Console Redirection->Console Redirection|Disabled|

