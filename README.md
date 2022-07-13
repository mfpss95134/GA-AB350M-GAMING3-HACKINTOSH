# ASUS-P8B75-M-LE-HACKINTOSH

## Specifications
| Component | Details |
|:---:|:---:|
| CPU | AMD Ryzen 5 1600 |
| RAM | Micron 16GB DDR4 2666Mhz<br>+<br>Transcend 16GB DDR4 3200Mhz |
| MB | GA-AB350M-Gaming 3 |
| SSD | Intel 760P 256GB |
| HDD | TOSHIBA DT01ACA200 2TB |
| iGPU | N / A |
| dGPU | ROG-STRIX-RX470-O4G-GAMING |
<br>

## Supported Versions
- macOS Catalina 10.15.7
- macOS Big Sur 11.6.5
- macOS Monterey 12.0.1
<br>

## Known Issues
Most parts are working well, except the following.

| Component | Status | Description |
|:---|:---|:---|
| Microphone | Not working | It's well known that AMD 15h/16h may have issues with AppleALC and Ryzen/Threadripper systems rarely have mic support.<br><br>If you really need a working mic, you can either buy an external usb sound card or install VoodooHDA.kext to /S/L/E (with SIP fully disabled).  |

<br>

## Recommended BIOS Settings
- Disable
  - Fast Boot
  - Secure Boot
  - Serial/COM Port
  - Parallel Port
  - CSM

  
  
- Enable
  - EHCI/XHCI Hand-off
  - OS type: Windows 8.1/10 UEFI Mode
  - SATA Mode: AHCI
<br>

## Screenshots
<br>

## Reference
- <https://www.youtube.com/watch?v=Fg7bDGs3JnQ>
- <https://mtwstudio.gitbook.io/ryzentosh/>
<br>

## Credits
- [**Apple**](https://www.apple.com/tw/) for the macOS.
- [**Dortania**](https://github.com/dortania) for the great guides.
- [**Acidanthera**](https://github.com/acidanthera) for [AppleALC](https://github.com/acidanthera/AppleALC), [Lilu](https://github.com/acidanthera/Lilu), [OpenCore](https://github.com/acidanthera/OpenCorePkg), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), [VirtualSMC](https://github.com/acidanthera/VirtualSMC), [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [**AMD OS X**](https://github.com/AMD-OSX/AMD_Vanilla) for the .

