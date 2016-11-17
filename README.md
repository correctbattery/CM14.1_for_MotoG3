# CM14.1_for_MotoG3
How to install CM14.1 on MotoG3 [2015] osprey

a.) Download to Workstation following file:
http://forum.xda-developers.com/devdb/project/?id=11051#downloads

b.) Install fastboot & adb

c.) Boot phone into bootloader

d.) On Workstation go to TWRP download folder and execute:

      adb reboot bootloader
      
      fastboot flash recovery twrp-3.0.x.x-xxx.img
      
      fastboot reboot

e.) Download ROM
https://www.cmxlog.com/14.1/osprey/

f.) Download GApps (mini)
http://opengapps.org/

g.) Wipe phone in TWRP

h.) Flash files
