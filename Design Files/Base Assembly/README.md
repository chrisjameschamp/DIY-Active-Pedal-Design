<h2 align="center">DIY Active Pedal Design - Base Assembly</h2>
<div align="center">
  <img width="800" alt="Header" src="https://github.com/chrisjameschamp/DIY-Active-Pedal-Design/blob/main/Design%20Files/Base%20Assembly/Images/Champ_BaseAssembly_V1.png">
</div>

## Index

- [Design](#design)
- [Print Settings](#print-settings)
- [Machined Parts](#machined-parts)
- [Hardware](#hardware)
  - [Hardware List](#hardware-list)
- [Assembly](#assembly)
- [License](#license)

## Design

The base assembly is the most critical component of the pedal system and houses the majority of mechanical and electronic elements.

It’s built around the [JLCPCB Linear Actuator (JKK60-5-P-150-A1-F4-M)](https://jlcmc.com/product/s/B16/BQD-JKK60/FA-%E7%9B%B4%E7%BA%BF%E8%BF%90%E5%8A%A8%E9%9B%B6%E4%BB%B6-%E9%92%A2%E5%88%B6%E7%9B%B4%E7%BA%BF%E6%A8%A1%E7%BB%84?productModelNumber=JKK60-5-P-150-A1-F4-M) and the [iSV57T-130S 130W NEMA 23 Servo Motor](https://www.omc-stepperonline.com/nema-23-integrated-easy-servo-motor-130w-3000rpm-0-45nm-63-73oz-in-20-50vdc-servo-motor-short-shaft-isv57t-130s). These work together to provide responsive, high-force motion to the pedal arm.

The base also provides space to mount electronics, including the control and power boards. This build uses the excellent designs by [gilphilbert](https://github.com/gilphilbert) — specifically the V1.1 Power Board and V1.2 Control Board, found here: [DIY-Sim-Racing-FFB-Pedal-PCBs](https://github.com/gilphilbert/DIY-Sim-Racing-FFB-Pedal-PCBs). These boards can be ordered mostly pre-assembled through [JLCPCB](https://jlcpcb.com); see Gil’s GitHub repo for full ordering instructions.

### Print Settings

The assembly was printed on a Creality K2 Plus, but your settings will vary depending on the printer and material used. Make sure your filament is well-tuned before printing — the enclosure is large and takes time to complete.

#### Recommended Print Settings

- **Wall loops**: At least 10
- **Top layers**: 12
- **Bottom layers**: 10
- **Infill**: 30% sparse gyroid
- **If using rectangular infill**: Use 40% or higher

⚠️ For nylon:
Thoroughly dry your filament before printing. Even slightly damp nylon will print poorly, resulting in weak layer adhesion and rough surface quality.

Due to the high wall/infill density, use a brim (10mm recommended) and possibly glue stick or other adhesion aid. I used both, and they were necessary to prevent warping.

### Machined Parts

Due to the size and stress this part experiences, it is strongly recommended to machine the base plate from **aluminum or steel** rather than printing it.

For budget-friendly CNC machining, [JLC CNC](https://jlccnc.com) is a solid option. They offer several materials including stainless steel, steel alloy, and aluminum.  
The recommended material is **6061 aluminum** with an **anodized finish**, offering a strong and lightweight plate at a reasonable cost. As of writing, a base plate typically costs **$25–$40 USD** plus shipping.

If machining isn’t an option, the base plate can be 3D printed in plastic. While not ideal, it can work when mounted to a rigid pedal tray or sim rig made from aluminum extrusion (e.g. Trak Racer or Sim-Lab). The printed version is split into **three parts** to accommodate smaller printers.

There are two versions of the rear base file:
- `Base_Rear_V1` — for use with a machined base plate
- `Base_Rear_Alt_V1` — includes additional nut insert support and works with both machined and printed base plates

## Hardware

The hardware used can mostly be sourced from [McMaster-Carr](https://www.mcmaster.com/).  
If you're substituting parts from your local hardware store or Amazon, be sure to double-check dimensions — they’re critical for proper fit and function.

### Hardware List

| **Item**                        | **Part Number** | **Qty** | **Link** |
|---------------------------------|-----------------|---------|----------|
| Linear Rail               | JKK60-5-P-150-A1-F4-M | 1       | [Link](https://jlcmc.com/product/s/B16/BQD-JKK60/FA-%E7%9B%B4%E7%BA%BF%E8%BF%90%E5%8A%A8%E9%9B%B6%E4%BB%B6-%E9%92%A2%E5%88%B6%E7%9B%B4%E7%BA%BF%E6%A8%A1%E7%BB%84?productModelNumber=JKK60-5-P-150-A1-F4-M) |
| 130w NEMA 23 Servo Motor        | iSV57T-130S     | 1       | [Link](https://www.omc-stepperonline.com/nema-23-integrated-easy-servo-motor-130w-3000rpm-0-45nm-63-73oz-in-20-50vdc-servo-motor-short-shaft-isv57t-130s) |
| Gilphilbert Control Board       | V1.2            | 1       | [Link](https://github.com/gilphilbert/DIY-Sim-Racing-FFB-Pedal-PCBs/tree/main/control-board) |
| Gilphilbert Power Board         | V1.1            | 1       | [Link](https://github.com/gilphilbert/DIY-Sim-Racing-FFB-Pedal-PCBs/tree/main/power-board) |
| FPC FFC PCB Converter Board 6P  | N/A             | 1       | [Link](https://a.co/d/bPsciNe) |
| FFC Ribbon Flat Flexible Cable, 6 Pin 0.5mm Pitch 300mm Long | N/A | 1 | [Link](https://a.co/d/6zGifmP) |
| 6 Pin PCIe Extension Cable      | N/A             | 1       | [Link](https://a.co/d/cVutRBN) |
| 16 Gauge Wire (Various Colors)  | N/A             |         | [Link](https://a.co/d/feJ6wWT) |
| Kapton Tape                     | N/A             |         | [Link](https://a.co/d/9xGHyLZ) |
| USB-C Extension                 | N/A             | 1       | [Link](https://a.co/d/dT4IqKd) |
| XT30 Connector Adapter          | N/A             | 1       | [Link](https://a.co/d/eTCltLF) |
| JST-XH Connectors               | N/A             |         | [Link](https://a.co/d/135aogA) |
| JST-XH Pin Header Connectors    | N/A             |         | [Link](https://a.co/d/96Qgd40) |
| RG178 U.FL MHF1 to SMA Coax Cable | N/A           | 1       | [Link](https://a.co/d/cNCmAZx) |
| 2.54mm 0.1" Pitch PCB Mount Screw Terminal Block | N/A | 1  | [Link](https://a.co/d/gwZj4TC) |
| M3x0.5mm Heat Set Insert        | 94180A333       | 7       | [Link](https://www.mcmaster.com/94180A333/) |
| M3x0.5 6mm Socket Head Screw    | 91292A111       | 8       | [Link](https://www.mcmaster.com/91292A111/) |
| M3x0.5 16mm Socket Head Screw   | 91292A115       | 4       | [Link](https://www.mcmaster.com/91292A115/) |
| M3x0.5 20mm Socket Head Screw   | 91292A123       | 2       | [Link](https://www.mcmaster.com/91292A123/) |
| M3x0.5 30mm Socket Head Screw   | 91292A022       | 1       | [Link](https://www.mcmaster.com/91292A022/) |
| M4x0.7mm Heat Set Insert        | 94180A353       | 12      | [Link](https://www.mcmaster.com/94180A353/) |
| M4x0.7 16mm Flat Head Screw   | 92125A196       | 12      | [Link](https://www.mcmaster.com/92125A196/) |
| M4x0.7 18mm Flat Head Screw   | 91292A043       | 4       | [Link](https://www.mcmaster.com/91292A043/) |
| M5x0.8mm Nut                    | 91828A241       | 6       | [Link](https://www.mcmaster.com/91828A241/) |
| M5x0.8mm Heat Set Insert        | 94180A363       | 5       | [Link](https://www.mcmaster.com/94180A363/) |
| M5x0.8 18mm Socket Head Screw   | 91292A127       | 2       | [Link](https://www.mcmaster.com/91292A127/) |
| M5x0.8 35mm Socket Head Screw   | 91292A193       | 4       | [Link](https://www.mcmaster.com/91292A193/) |
| M5x0.8 30mm Socket Head Screw   | 91292A192       | 4       | [Link](https://www.mcmaster.com/91292A192/) |

### Notes

1. **Linear Rail** – The part number calls for the 5 pitch screw, however the 10 pitch can also be used but not recommended for the brake pedal.  The 10 pitch is a better fit for the throttle / clutch pedal which requires faster movement with less force resistance.
2. **FPC FFC PCB Converter Board 6P** - The complete build includes **2** of these boards so plan your order accordingly.
3. **PCIe Extension Cables** – The full pedal setup requires a total of **6** cables. You’ll need 3 for the PSU and 3 for the pedals, so plan your order accordingly.

## Assembly

A complete walkthrough of the assembly process can be found on the [Wiki](https://github.com/chrisjameschamp/DIY-Active-Pedal-Design/wiki/)

## License

These 3D design files are licensed under a [Creative Commons BY-NC-SA 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

You may:
- Use and remix these files for **personal, non-commercial purposes**.
- Share modified versions, as long as they are also non-commercial, include credit, and use the **same license**.

You may NOT:
- Use these files or derivatives **for commercial use**.
- Re-license modified versions under more restrictive or proprietary terms.

Please credit **@ChrisJamesChamp** and link back to this repository if you use, remix, or share these designs.
