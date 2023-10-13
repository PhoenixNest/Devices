this has limited testing.  DO THIS AT YOUR OWN RISK.  no one is responsible for your actions except you!

prereqs:
1) download zip
2) extract zip somewhere like your desktop
3) plugin onegx1 pro and have a well charged battery
4) turn off undervolting (not a thing) and anything else that could lead to instability.  you are flashing a bios.

flash unlocked bios:
1) open command prompt as admin
2) cd to the location you extracted the zip
3) run 1-Update.cmd.  your bios is flashing.  do not touch it.
4) if it succeeds (it should), click start, click power, hold shift, click restart.  choose turn off your pc.
5) wait about 10 seconds after the blue led goes out.
6) power on device, start mashing delete.
7) in the bios, press Fn+3 (Function3) to load optimized defaults.  press Fn+4 (Function4), yes to save and load windows.

flash PTT-enabled bios:
1) open command prompt as admin
2) cd to the location you extracted the zip
3) run 2-UpdatePTT.cmd.  your bios is flashing.  do not touch it.
4) if it succeeds (it should), in the same command prompt window run FPTW64new -greset
5) windows will automatically restart
6) the blue led will come on, the fan will come on after a few seconds and the ME will reset.
7) the ME reset will take a minute or more.  do not panic.  do not touch it.
8) eventually the bios logo will come up.  the bios logo may blink off the first time and reset.  this is fine.  it is training the memory.
9) allow windows to load and look for TPM.
