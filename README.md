# Preliminary HSI reports
HSI reports for various platforms that haven't yet been listed on https://fwupd.org/lvfs/hsireports/devices.

---

**Table of Content**


 - [Introduction](#introduction)
 - [Disclaimer](#disclaimer)
 - [Database](#database)
 - [Contribute](#contribute)

---

### Introduction

The [device list](https://fwupd.org/lvfs/hsireports/devices) on fwupd's website lists many platforms, but apparently it needs more than a single report to file a new entry, leaving many reported systems unpublished. This database lists platforms that haven't yet been reported to fwupd often enough to warrant an entry. 

### Disclaimer

This is a community effort and not an official list. I'm neither endorsed nor affiliated by any of the listed vendors or the Linux Vendor Firmware Service Project. All of the information on this site is presented as is and should not be the basis of any purchase decision. If you need definite information on hardware security features **DO NOT RELY ON THIS LIST**. Contact the vendor or firmware provider.

## Database

| Vendor  | Model | Firmware version | fwupdmgr version | Comments | HSI level | Link to full report |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| ASRock | [X570 Phantom Gaming-ITX/TB3](https://pg.asrock.com/mb/AMD/X570%20Phantom%20Gaming-ITXTB3/index.asp) | 5.67 [Beta] |v2.0.16 | | HSI:1 | [Link](https://github.com/PerAstraAdDeum/Preliminary-HSI-reports/blob/main/Reports/asrock.x570-itxtb3.5.67.txt) |
| ASUS | [ASUS Maximus Impact VI](https://rog.asus.com/motherboards/rog-maximus/rog-maximus-vi-impact/) | 1603 | v2.0.18 | | HSI:0 | [Link](https://github.com/PerAstraAdDeum/Preliminary-HSI-reports/blob/main/Reports/asus_maximus_impact_vi.1603.txt) |
| ASUS | [ASUS TUF GAMING B560M-PLUS](https://www.asus.com/motherboards-components/motherboards/tuf-gaming/tuf-gaming-b560m-plus/) | 2001 | v2.0.18 | | HSI:0 | [Link](https://github.com/PerAstraAdDeum/Preliminary-HSI-reports/blob/main/Reports/asus.tuf_b560m-plus.2001.txt)
| ASUS | [ASUS ROG Strix Z690-A Gaming WIFI](https://rog.asus.com/motherboards/rog-strix/rog-strix-z690-a-gaming-wifi/) | 4505 | v2.0.18 | | HSI:1 | [Link](https://github.com/PerAstraAdDeum/Preliminary-HSI-reports/blob/main/Reports/asus.rog_z690-a-gaming.4505) |
| ASUS | [ASUS ROG Strix Z890-I Gaming WIFI](https://rog.asus.com/motherboards/rog-strix/rog-strix-z890-i-gaming-wifi/) | 2201 | v2.0.18 | | HSI:1 | [Link](https://github.com/PerAstraAdDeum/Preliminary-HSI-reports/blob/main/Reports/asus.rog_z890-i.2201.txt) |
| NovaCustom | [V54 (Intel)](https://novacustom.com/product/v54-series/) | 1.0.0 | v2.0.18 | Based on coreboot. | HSI:3 | [Link](https://github.com/PerAstraAdDeum/Preliminary-HSI-reports/blob/main/Reports/novacustom.v54.1.0.0.txt) |

## Contribute

1. Make sure that your BIOS is up to date.
2. Run `fwupdmgr security` and copy the contents of the report (remember to also use the auto-report feature when asked).
3. If you wish, omit the last part detailing the security events history.
4. Create a new issue or send the report to me.
