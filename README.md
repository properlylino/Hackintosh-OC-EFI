![Banner](https://i.imgur.com/cGRapOD_d.webp?maxwidth=760&fidelity=grand)
<br>
# ASUS-X550CA-OC-EFI
EFI files compatbile with the asus x550ca laptop
<br>
if it works, please give the repository a star.
<br>
### Hardware
|     Name     |        Model        |
| :----------: | :-----------------: |
|     CPU      |      Intel(R) Core(TM) i3-3217U CPU @ 1.80GHz      |
|     IGPU     |      Intel HD Graphics 4000      |
|     RAM      |      4GB onboard + 4GB DDDR3      |
|     Storage  |      (2x) HDD Seagate 465gb       |
|     Network  |      Qualcomm Atheros AR9485 Wireless Network Adapter |
|     Display  |      15.6" HD 60Hz, 1366 x 768      |
|     Sound    |      Realtek ALC270      |
|     Ethernet |      Realtek RTL8168/8111 PCI-E Gigabit Ethernet Adapter     |

### Working
* CPU power management
* Wi-Fi & Bluetooth & Ethernet
* USB Ports
* Sleep & Wake
* FN keys
* iCloud, iMessage, FaceTime

### Issues
Network adapter works, but it is VERY slow. I advise you to change it to a Bcm94360cs2 (broadcom)
<br>
Sound doesn't work, i tried every single AppleALC layout and it simply refuses to work.
<br>
Couldn't test trackpad as the flat cable / connector of mine is broken. If you plan on using, open the config.plist file and find the VoodooPS2Trackpad.kext & VoodooPS2Mouse.kext kexts thing. Then, enable both of them.

### Notes
it comes with no platforminfo. i used a MacBookPro12,1 as the product.
<br>
tested on macOS Big Sur (11.7.10)
<br>
make sure to change some options in your bios.

### BIOS Values
* `Advanced - USB Configuration - XHCI Pre-Boot Mode` **Enabled**
* `Advanced - USB Configuration - Legacy USB Support` **Enabled**
* `Boot - Launch CSM` **Disabled**
* `Security - Secure Boot Control` **Disabled**

