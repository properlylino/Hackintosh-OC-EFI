![Banner](https://raw.githubusercontent.com/properlylino/Hackintosh-OC-EFI/refs/heads/main/img/banner.png)
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
Keyboard
<br>
All Apple Services (or most of them)
<br>

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
thanks Dream471 for the readme file base
