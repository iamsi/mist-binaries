BBC Micro for MIST
==================

This is a port of Mike Sterlings great [BBC Micro on FPGA](http://www.mike-stirling.com/retro-fpga/bbc-micro-on-an-fpga/) with major changes by Stephen Leary. 

This core includes os1.2, basic2 and SuperMMC. It implements a
[MMBEEB](http://swhs.home.xs4all.nl/bbc/mmbeeb/) compatible interface
and can use it to load software from SD card. The limitations of the original
mmbeed still apply and e.g. the SD card needs to be DAT16 formatted and the
'beeb.mmb' file needs to be written first to the SD card before anything else.

A 16k ROM image can be uploaded to Sideways ROM slot 13 using the OSD. 

This is a work in prgress and e.g. the current version still has a
major bug in the video timing and the display is slightly corrupted.
