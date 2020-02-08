# General card informations
audio chip shows :
ENSONIQ
ES1370
AudioPCI
ES1370-0001-01
H1160
NBD0239 TW
HKG9611

Infos by Speedsys 4.78
VendorID : 1274, DeviceID : 5000
labeled as "Creative SoundBlaster PCI64"

# FreeDOS 1.2
Based on [Vogons forum post](https://www.vogons.org/viewtopic.php?t=41605) linking to this [FTP mirror](ftp://89.179.20.136/oldftp/DRV&BIOS/Sound/ENSONIQ/ES1370/DOS/)
This will provide "ENSONIQ AudioPCI Initialization Driver, Version 2.37"
- Load FreeDOS with EMM386 (Expanded Memory) and SHARE loaded, the driver wants EMS
- copy EAPCI folder to your FreeDOS 1.2 C:\ partition
- add content of supplied AUTOEXEC.BAT to your system's AUTOEXEC.BAT
- reboot (or manually rerun AUTOEXEC.BAT)


# Misc informations
Tested on ASROCK K7VT4A Pro : 
ENSONIQ drivers 2.37 seems unstable on FreeDOS 1.2 :
- Sometimes aptest.exe doesn't detect the PCI card, "Grand Piano" MIDI test sounds glitchy and not like piano at all
- Wolf3D crashes when enabling SoundBlaster audio sounds
- Settlers2 sound setup detects ensoniq fine but s2.exe doesn't start after PS2 mouse discovery
