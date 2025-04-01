<h2 align="center">DIY Active Pedal Design - Power Supply</h2>
<div align="center">
  <img width="800" alt="Header" src="https://github.com/chrisjameschamp/DIY-Active-Pedal-Design/blob/main/Design%20Files/Power%20Supply/Images/Champ_PowerSupply_V1.png">
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

This power supply enclosure is entirely optional to build, however it hides the power connections, adds a power switch, and utilizes a standized cable configuration that is safe and easy to use.

The power supply enclosure is built around the [MEANWELL LRS-600-36](https://www.omc-stepperonline.com/lrs-600-36-mean-well-597-6w-36vdc-16-6a-115-230vac-enclosed-switching-power-supply-lrs-600-36), other power supply units may work but dimensions and specs may vary so do so at your own risk.

## 3D Printing

The power supply enclosure is designed to be 3d printed, it could be CNC machined as well, although it would probably not be super easy and/or cheap.  If it were to be CNC machined however, there are a lot of areas that could be simplified or adjusted with drill taps to eliminate the use of some hardware.

### Material Options

I’ve only tested this part printed in eSun’s [ePA-CF](https://a.co/d/0XDH10W), an 80/20 nylon-carbon fiber composite with excellent strength, layer adhesion, and added rigidity from the carbon fiber. It also has relatively high tensile strength.

More affordable options like PETG+CF or ABS+CF composites may work as well. Unlike the majority of the parts on the pedals, the strength of the power supply enclosure is not nearly as important therefore printing with PETG+CF or ABS+CF might actually make more sense in regards to affordablity and ease of printing.

### Print Settings

The power supply enclosure was printed on a Creality K2 Plus, but print settings will vary depending on your printer and material. Make sure your filament and printer are well-tuned before attempting a full print — it’s a large part and can take quite a while.  The larger piece of the power supply enclodure is just over 280mm wide and will not fit on most printers.  I have included a sliced version that can be printed on smaller print beds, this version has not been tested but should work just the same.

#### Recommended Print Settings

- **Wall loops**: At least 4
- **Top layers**: 5
- **Bottom layers**: 4
- **Infill**: 20% sparse gyroid
- **If using rectangular infill**: Use 30% or higher

⚠️ For nylon:
Thoroughly dry your filament before printing. Even slightly damp nylon will print poorly, resulting in weak layer adhesion and rough surface quality.

Due to the high wall/infill density, use a brim (10mm recommended) and possibly glue stick or other adhesion aid. I used both, and they were necessary to prevent warping.

## Hardware

The hardware I used can mostly be sourced from [McMaster-Carr](https://www.mcmaster.com/).  
If you're substituting parts from your local hardware store or Amazon, be sure to double-check dimensions — they're critical for fit and function.

### Hardware List

| **Item**                        | **Part Number** | **Qty** | **Link** |
|---------------------------------|-----------------|---------|----------|
| MEANWELL LRS-600-36             | N/A             | 1       | [Link](https://www.omc-stepperonline.com/lrs-600-36-mean-well-597-6w-36vdc-16-6a-115-230vac-enclosed-switching-power-supply-lrs-600-36) |
| IEC Connector with Power Switch | 5428N111        | 1       | [Link](https://www.mcmaster.com/5428N111/) |
| M3x0.5mm Heat Set Insert        | 94180A333       | 6       | [Link](https://www.mcmaster.com/94180a333/) |
| M3x0.5 14mm Flat Head Screw     | 92125A133       | 4       | [Link](https://www.mcmaster.com/92125A133/) |
| M3x0.5 18mm Flat Head Screw     | 92125A135       | 2       | [Link](https://www.mcmaster.com/92125A135/) |
| M4x0.7 10mm Flat Head Screw     | 92125A190       | 10      | [Link](httos://www.mcmaster.com/92125A190/) |
| 6 Pin PCIe Extension Cable      | N/A             | 3       | [Link](https://a.co/d/cVutRBN) |

### Notes

1. **M4 Flat Head Screws** – These screws should  not be any longr than 10mm, any longer and it could damage the unit.
2. **PCIe Extension Cable** – The total project needs a total of 6 cables, keep that in mind when ordering.

## Assembly

Coming soon — I’ll be adding step-by-step instructions and photos here once testing is complete.

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