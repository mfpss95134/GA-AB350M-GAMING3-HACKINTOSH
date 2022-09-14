# GA-AB350M-GAMING3-HACKINTOSH

## Specifications
| Component | Details |
|:---:|:---:|
| CPU | AMD Ryzen 5 1600 |
| RAM | Transcend 16GB DDR4 3200Mhz |
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
| USB | Working | Although USB is working out of box, most tutorials still recommend us to do USB mapping.<br><br>I have no idea whether I should do USB mapping because USB mapping on AMD platform seems to be very complicated. |
<br>


## Recommended BIOS Settings
  - Disable
    - Fast Boot
    - CSM Support
    - Secure Boot
    - AMD CPU fTPM
    - Above 4G Decoding
    - Serial/COM Ports
    - Parallel Ports
	
	
  - Enable
    - SVM Mode
    - EHCI/XHCI Hand-off
    - SATA Mode: AHCI
<br>


## Screenshots
<div align="center">
<img src="https://github.com/mfpss95134/GA-AB350M-GAMING3-HACKINTOSH/blob/main/IMAGEs/01.png">
<img src="https://github.com/mfpss95134/GA-AB350M-GAMING3-HACKINTOSH/blob/main/IMAGEs/02.png">
<img src="https://github.com/mfpss95134/GA-AB350M-GAMING3-HACKINTOSH/blob/main/IMAGEs/03.png">
<img src="https://github.com/mfpss95134/GA-AB350M-GAMING3-HACKINTOSH/blob/main/IMAGEs/04.png">
<div align="left">
<br>


## Reference
- <https://www.youtube.com/watch?v=Fg7bDGs3JnQ>
- <https://mtwstudio.gitbook.io/ryzentosh/>
<br>


## Credits
- [**Apple**](https://www.apple.com/tw/) for the macOS.
- [**Dortania**](https://github.com/dortania) for the great guides.
- [**Acidanthera**](https://github.com/acidanthera) for [AppleALC](https://github.com/acidanthera/AppleALC), [Lilu](https://github.com/acidanthera/Lilu), [OpenCore](https://github.com/acidanthera/OpenCorePkg), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), [VirtualSMC](https://github.com/acidanthera/VirtualSMC), [WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [**AMD OS X**](https://github.com/AMD-OSX/AMD_Vanilla) for the crucial patches.
