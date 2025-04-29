<h2 align="center">DIY Active Pedal Design - Slider</h2>
<div align="center">
  <img width="800" alt="Header" src="https://github.com/chrisjameschamp/DIY-Active-Pedal-Design/blob/main/Design%20Files/Slider/Images/Champ_Slider_V1.png">
</div>

## Index

- [Design](#design)
- [3D Printing](#3d-printing)
   - [Material Options](#material-options)
   - [Print Settings](#print-settings)
- [Hardware](#hardware)
   - [Hardware List](#hardware-list)
- [Assembly](#assembly)
- [License](#license)

## Design

The slider is designed to be simple, functional, and easy to assemble.

## 3D Printing

The slider is designed to be 3d printed, it could be CNC machined as well, although it would probably not be super easy and/or cheap.  If it were to be CNC machined however, there are a lot of areas that could be simplified or adjusted with drill taps to eliminate the use of some hardware.

### Material Options

I’ve only tested these parts printed in eSun’s [ePA-CF](https://a.co/d/0XDH10W), an 80/20 nylon-carbon fiber composite with excellent strength, layer adhesion, and added rigidity from the carbon fiber. It also has relatively high tensile strength.

You could try pure nylon, although it might be too flexible.

More affordable options like PETG+CF or ABS+CF composites may work as well. While they likely have enough strength in the XY axis (which is how the part is oriented for printing), I’m less confident in their Z-axis strength due to weaker layer bonding.

Some users in the DIY FFB Pedal Discord have reported success with PLA+ or regular PETG. I haven’t tested these myself, and I’d be cautious about PLA+’s long-term durability.

The **Slider_Shield** is not structural and does not need to be printed in nylon.  I personally printed and tested it with [Fiberon's PETG-CF](https://a.co/d/dX2OyLc).

### Print Settings

The slider was printed on a Creality K2 Plus, but print settings will vary depending on your printer and material.

#### Recommended Print Settings

- **Wall loops**: At least 10
- **Top layers**: 12
- **Bottom layers**: 10
- **Infill**: 30% sparse gyroid
- **If using rectangular infill**: Use 40% or higher

⚠️ For nylon:
Thoroughly dry your filament before printing. Even slightly damp nylon will print poorly, resulting in weak layer adhesion and rough surface quality.

## Hardware

The hardware I used can mostly be sourced from [McMaster-Carr](https://www.mcmaster.com/).  
If you're substituting parts from your local hardware store or Amazon, be sure to double-check dimensions — they're critical for fit and function.

### Hardware List

| **Item**                        | **Part Number** | **Qty** | **Link** |
|---------------------------------|-----------------|---------|----------|
| M3x0.5mm Heat Set Insert        | 94180A333       | 2       | [Link](https://www.mcmaster.com/94180A333/) |
| M3x0.5 4mm Socket Head Screw    | 91292A109       | 2       | [Link](https://www.mcmaster.com/91292A109/) |
| M3x0.5 6mm Flat Head Screw      | 92125A126       | 2       | [Link](https://www.mcmaster.com/92125A126/) |
| M3x0.5 10mm Flat Head Screw     | 92125A130       | 2       | [Link](https://www.mcmaster.com/92125A130/) |
| M4x0.7 Standard Nut             | 91828A241       | 4       | [Link](https://www.mcmaster.com/91828A241/) |
| M4x0.7 14mm Socket Head Screw   | 91292A038       | 2       | [Link](https://www.mcmaster.com/91292A038/) |
| M4x0.7 30mm Socket Head Screw   | 91292A130       | 2       | [Link](https://www.mcmaster.com/91292A130/) |
| M5x0.8 16mm Socket Head Screw   | 91292A126       | 2       | [Link](https://www.mcmaster.com/91292A126/) |
| M5x0.8 45mm Socket Head Screw   | 91292A195       | 2       | [Link](https://www.mcmaster.com/91292A195/) |
| 8mm x 40mm Dowel Pin            | 91585A829       | 1       | [Link](https://www.mcmaster.com/91585A829/) |
| FPC FFC PCB Converter Board 6P  | N/A             | 1       | [Link](https://a.co/d/bPsciNe) |


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

##

<div align="center">
  <a href="https://paypal.me/Champeau?country.x=US&locale.x=en_US"><img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black"></a>
</div>