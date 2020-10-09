# 6row_pcb
## A QMK-compatible controller for the 6-row Lenovo Thinkpad Classic Keyboard

Based on the excellent work by lowJ and his tp-keyboard project: https://github.com/lowJ/tp-keyboard

This project aims to create an easy-to-build **through-hole only** QMK-compatible USB controller for a six row ThinkPad keyboard (L410, L420 etc) and x61 trackpoint, based on the ATMega324PA-PN microcontroller.

**QMK Firmware:** https://github.com/wren4777/6row_fw

**Matrix (untested!):** https://docs.google.com/spreadsheets/d/1tQ2VNZjKjTMB-WhVCuyUlhV_uuDBqxDxuXh8Zw81a1k/edit?usp=sharing

**Why six row over seven?**

Unfortunately, as wonderful as the classic seven row ThinkPad keyboard on the T420 and similar is, it uses a difficult to source and difficult to solder surface-mount connector. The six row keyboards, as found on the L410 and later, use a standard 30-pin 1mm FFC connector, allowing for easy integration with an external controller.

**Why do I need to replace my Trackpoint?**

The Trackpoint that comes with these keyboards unfortunately isn't documented very well, so it's recommended to take a known good one from one of the models listed below.

**The ATMega324PA-PN is expensive, can I use a normal ATMega32A?**

Yes, just follow the directions to adapt the code on the firmware repository linked above. At the time this project started, the 324PA was cheaper than the 32A, hence its use.

**Compatible ThinkPad Keyboards**

* L420
* L410
* L412
* L421 
* L510 
* L512 
* L520 
* SL410
* SL410K 
* SL510 
* SL510K

**NOT compatible**

* Any ThinkPad whose model starts with T or W
* Any other ThinkPad whose keyboard has seven rows

**Compatible ThinkPad Trackpoints**

* R61
* X61
* T61

**Contact**

Reddit - u/wren4777

Discord - Wren#2829

**Gerbers and firmware info coming soon!**
