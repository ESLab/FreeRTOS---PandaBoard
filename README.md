FreeRTOS---PandaBoard
=====================

This port runs two separate FreeRTOS instances on the Dual-Core Pandaboard. Standard FreeRTOS demos are provided and run on each core.

The port contains a makefile which loads the binaries directly to the ram of the Pandaboard with ymodem. All boot settings are provided in the makefile. To run the demo execute "make" and "make upload". Make sure that you have a usb-to-serial adapter between the PC and the Pandaboard (the makefile is by default set to use /dev/ttyUSB0). The upload script requires expect to be installed.

You can download it as a package from the Downloads tab: https://github.com/ESLab/FreeRTOS---PandaBoard/downloads

This port was created by the Department of Information Technologies at Åbo Akademi University (https://research.it.abo.fi/)

[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/43803b4faf68903b039254335894c3c9 "githalytics.com")](http://githalytics.com/ESLab/FreeRTOS---PandaBoard)
