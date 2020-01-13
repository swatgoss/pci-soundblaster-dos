# General card informations
EMU10K1 audio chip

# DOS 6.22
Based on [Vogons "Sound Blaster Live! PCI Drivers for DOS"](http://vogonsdrivers.com/getfile.php?fileid=52&menustate=0) but modified some path to DOSDRV instead of drv subfolder for cleaner install file structure (single DOSDRV folder without any external reference)
- copy DOSDRV folder to your DOS 6.22 C:\ partition
- add content of supplied AUTOEXEC.BAT to your system's AUTOEXEC.BAT (allowing PCI card initialization using C:\DOSDRV\SBEINIT.COM)
- reboot (or manually rerun AUTOEXEC.BAT)
- test the soundcard with C:\DOSDRV\SBEGO.EXE

# Misc informations
https://wiki.debian.org/fr/snd-emu10k1

https://assets.hardwarezone.com/2009/reviews/sound/roundup/soundcards.htm
