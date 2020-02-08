# Original author
Mau1wurf1977 on http://vogons.zetafleet.com

# General card informations
audio chip shows :
CREATIVE
ES1373
ES1373-0001-05
S       JM480A
0043       Kor

Infos by Speedsys 4.78
VendorID : 1274, DeviceID : 1371
labeled as "Creative (Was: Ensoniq) AudioPCI-97 ES1371"

# FreeDOS 1.2
Based on [Vogons "Ensoniq AudioPCI DOS Drivers"](http://vogonsdrivers.com/getfile.php?fileid=373&menustate=0)
- Load FreeDOS with EMM386 (Expanded Memory) and SHARE loaded, the driver wants EMS
- copy AUDIOPCI folder to your FreeDOS 1.2 C:\ partition
- add content of supplied AUTOEXEC.BAT to your system's AUTOEXEC.BAT
- reboot (or manually rerun AUTOEXEC.BAT)


# Misc informations
The card is low profile, appears to be a DELL 0088GF and correspond to Creative's product "Sound Blaster Audio Pci 64 Dell oem"

Tested on ASROCK K7VT4A Pro :
- PCI slots 1 and 4 interfere with PCI device detection by the driver
- PCI slots 2,3 and 5 work as intended