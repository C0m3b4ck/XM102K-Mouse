# XM102K Mouse in KiCAD 
[@PrinterFixer](https://www.youtube.com/@PrinterFixer)
[Video title here](VIDEO HERE - IF THERE IS NONE THEN IT IS NOT DONE)

KiCAD project with GERBER and DRILL files of the XM102K mouse PCB from 2012/02/03, remade manually by me, C0m3b4ck. All models of all components are in place, the PCB is of accurate size. The only inacurracies are the connections, which aren't 1:1 to the actual PCB. The microswitch and the rotary encoder are the exact same but from different companies (couldn't find original companies).

**The mouse is commonly dropshipped from China under many companies.** 

## Purpose

This repository preserves the complete investigation of the XM102K mouse hardware: project files, documentation and images.
It is intended as a technical reference for anyone analyzing, repairing, or getting inspired by the XM102K design and the MX8733B-based optical mouse architecture.

## GERBER, DRILL and BOM (click to download)
* [Full labelling and components](https://github.com/C0m3b4ck/XM102K-Mouse/blob/main/XM102K-GERBER-DRILL-FULL.7z)
* [Only soldered compoenents](https://github.com/C0m3b4ck/XM102K-Mouse/blob/main/XM102K-GERBER-DRILL.7z)
* [Bill of Materials in .CSV](https://github.com/C0m3b4ck/XM102K-Mouse/blob/main/XM102K-BOM.csv)
## Components:
* MX8733B IC - [documentation included](https://github.com/C0m3b4ck/XM102K-Mouse/blob/main/DOCS/MX8733B.pdf),
* Illinois KXM Capacitor 100uf - [documentation included](https://github.com/C0m3b4ck/XM102K-Mouse/blob/main/DOCS/Omron-D2F-01-A-datasheet.pdf),
* 68ohm resistor,
* Omron D2F-01 microswitch - [documentation included](https://github.com/C0m3b4ck/XM102K-Mouse/blob/main/DOCS/Omron-D2F-01-A-datasheet.pdf) (same as on PCB but from a different company),
* 2-pin LED,
* 3-pin AlpsAlpine Rotary Encoder,

## Repository layout

- `DOCS/` — component datasheets and board photos.
- mouse1/mouse1/mouse1-1/mouse1-1.kicad_pro - project file.
- `XM102K-GERBER-DRILL.7z` — archived Gerber/drill package.
- `Xtreme-XM102K/` — KiCAD project files - models, footprints, symbols, schematic and PCB.

## Images
| | | | |
|---|---|---|---|
| <div align="center"><img src="DOCS/pcb_underside.png" alt="Virtual PCB underside" width="250"><br><sub>PCB 3D view in KiCAD - underside.</sub></div> | <div align="center"><img src="DOCS/pcb_top.png" alt="Virtual PCB top" width="250"><br><sub>PCB 3D view in KiCAD - top view.</sub></div> | <div align="center"><img src="DOCS/pcb_left.png" alt="Virtual PCB left" width="250"><br><sub>PCB 3D view in KiCAD - left.</sub></div> | <div align="center"><img src="DOCS/pcb_right.png" alt="Virtual PCB right" width="250"><br><sub>PCB 3D view in KiCAD - right.</sub></div> |
| <div align="center"><img src="DOCS/IMG_6731.png" alt="PCB underside" width="250"><br><sub>The underside of the PCB.</sub></div> | <div align="center"><img src="DOCS/IMG_6728.png" alt="PCB top view" width="250"><br><sub>View of the PCB from top.</sub></div> | <div align="center"><img src="DOCS/IMG_6729.png" alt="PCB left view" width="250"><br><sub>View of the PCB from the left.</sub></div> | <div align="center"><img src="DOCS/IMG_6730.png" alt="PCB right view" width="250"><br><sub>View of the PCB from the right.</sub></div> |
| <div align="center"><img src="DOCS/IMG_6143.png" alt="Stock board overview" width="250"><br><sub>The mouse case, stock photo.</sub></div> | <div align="center"><img src="DOCS/IMG_6684.png" alt="Full case and cable from top" width="250"><br><sub>Full mouse case and cable view from top.</sub></div> |  |  |

## Component documentation from 

These PDFs document the main components found on the board:

- [CAPPRD_Illinois_Capacitor_KXM_Series.pdf](DOCS/CAPPRD_Illinois_Capacitor_KXM_Series.pdf) — Illinois Capacitor KXM series (bulk electrolytic capacitors).
- [MX8733B.pdf](DOCS/MX8733B.pdf) — MX8733B 8-pin mouse sensor datasheet used by the XM102K.
- [Omron-D2F-01-A-datasheet.pdf](DOCS/Omron-D2F-01-A-datasheet.pdf) — Omron D2F-01-A microswitch datasheet for mouse buttons.
