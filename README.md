# CoPiCo PCB KiCad Files

The CoPiCo is a cartridge for the Tandy Color Computer that adds WiFi to and
serves as a boot ROM for the system. It is based on the Raspberry Pi Pico W
microcontroller dev board, which includes onboard WiFi.

![copico_pcb_rev0 1_front](https://github.com/thomasshanks/copico-board/assets/12594889/59d96e60-4434-4ec9-bde2-a83d828fd465)

![copico_pcb_rev0 1_back](https://github.com/thomasshanks/copico-board/assets/12594889/e07aa954-f644-40c8-9ac1-5fedec6be4f7)

![copico_rev0 1_schematic](https://github.com/thomasshanks/copico-board/assets/12594889/dc186fd7-bd3a-4350-a1a7-f4d89a8e7ffe)
[copico_rev0.1_schematic_v0.1.9.pdf](https://github.com/thomasshanks/copico-board/files/14322771/copico_rev0.1_schematic_v0.1.9.pdf)

## WiFi Connectivity

The firmware (see 'copico-firmware' repo) will behave more like a SPI WiFi
module or the WizNet chip (or perhaps both, depending on mode). It will, of
course, also allow listing and connecting to the desired WiFi network.

## ROM Emulation

CoPiCo will also support boot ROM emulation (initially just for a 1 KB ROM due
to limitations of first revision of the CoPiCo PCB). Henry Strickland
(@strickyak) plans to use this feature to load a version of his
"axiom" network boot ROM (see
https://github.com/strickyak/frobio/tree/main/frob3/booting).

## Other Future Capabilities

Future capabilities for the CoPiCo may include:
- VGA or HDMI output based on the captured contents of video RAM
- Logic capture / bus trace
- Remote debug, with breakpoints and watchpoints

## Stay Tuned to This Channel

Please star this repo and/or watch this space for updates as development
continues!

Thank you for being a part of the Retrocomputing community!


Thomas Shanks (copico@tshanks.org)    
13 Feb 2024
