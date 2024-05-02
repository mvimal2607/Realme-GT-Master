# flashing_instruction

Flashing instructions:

1.Download platform tool and Recommended recovery

2.Extract platform tool and recovery on same folder

3.Reboot to Bootloader

4.Then Run flash.bat(Windows) / flash.sh(Linux)

5.It will reboot to recovery

6.Do Factory reset

7.Then select apply update> apply from ADB

8.Then run command `adb sideload` <rom.zip> (After 47%, it will come one popup for installing additional package -- click No)

9.Factory reset (must)

10.Reboot system now.
