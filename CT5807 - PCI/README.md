# Original author
Mau1wurf1977 on http://vogons.zetafleet.com

# General card informations
ES1373 audio chip

# FreeDOS 1.2
Based on [Vogons "Ensoniq AudioPCI DOS Drivers"](http://vogonsdrivers.com/getfile.php?fileid=373&menustate=0)
- Load FreeDOS with EMM386 (Expanded Memory) and SHARE loaded, the driver wants EMS
- copy AUDIOPCI folder to your FreeDOS 1.2 C:\ partition
- add content of supplied AUTOEXEC.BAT to your system's AUTOEXEC.BAT
- reboot (or manually rerun AUTOEXEC.BAT)


# Misc informations
Tested on ASROCK K7VT4A Pro :
- PCI slots 1 and 4 interfere with PCI device detection by the driver
- PCI slots 2,3 and 5 work as intended