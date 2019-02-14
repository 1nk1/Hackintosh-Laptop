# Hackintosh <br> 
_(HP Pavilion G6-2286sr modified)_


#### Hardware System reequirements:
> **System**: _MacOS High Sierra 10.13.6_ <br>                           
> **Processor**: _Intel Core i5 (2,49Ghz)_ <br>
> **Memory**: _2 Bank for 4Gb Kingston (8Gb DDR3 1600Mhz)_ <br>
> **SSD**: _Samsung 850 EVO 250 (256Gb)_ <br>
> **Wifi**: _Atheros AR9285_ <br>
> **Ethernet**: _Realtek RTL8105E PCI_ <br>
> **Graphics**: _Intel HD 4000 (1536Mb)_ <br>
> **Sound**: _IDT92HD87B2/4_ <br>

### Kext directory included:
- [x] RealtekRTL8100.kext <br>
- [x] USBInjectAll.kext <br>
- [x] WhateverGreen.kext <br>
- [x] Lilu.kext <br>
- [x] HibernationFixup.kext <br>
- [x] CPUFriend.kext <br>
- [x] ApplePS2SmartTouchPad.kext <br>
- [x] FakeSMC.kext <br>
    |_ FakeSMC_ACPISensors.kext <br>
    |_ FakeSMC_CPUSensors.kext <br>
    |_ FakeSMC_GPUSensors.kext <br>
    |_ FakeSMC_LPCSensors.kext <br>
    |_ FakeSMC_SMMSensors.kext <br>

### Write a current guide:

```bash
$ cd ~/Downloads
$ git clone git@github.com:1nk1/Hackintosh-Laptop.git
```

#### Download:
| [Clover](https://sourceforge.net/projects/cloverefiboot/) | [MacIASL](https://github.com/acidanthera/MaciASL/releases) | [DPCIManager](https://sourceforge.net/projects/dpcimanager/) | [KextUtility](http://cvad-mac.narod.ru/files/Kext_Utility.app.v2.6.6.zip) | [Clover Configurator](https://mackie100projects.altervista.org/download-clover-configurator/) |


> Install `Clover` on local machine => 
> After copy downloaded directory `EFI` for local =>
> And replaced file! <br>
