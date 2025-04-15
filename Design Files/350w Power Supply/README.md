<h2 align="center">DIY Active Pedal Design - 350w Power Supply</h2>

<div align="center">
  <img width="800" alt="Header" src="https://github.com/chrisjameschamp/DIY-Active-Pedal-Design/blob/main/Design%20Files/350w%20Power%20Supply/Images/Champ_350w_PowerSupply_V1.png">
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

This power supply enclosure is completely optional to build, but it adds a few nice features: it hides the power connections, includes a power switch, and uses a standardized cable configuration that’s safe and easy to work with.

The enclosure is built around the [MEANWELL LRS-350-36](https://www.omc-stepperonline.com/lrs-350-36-mean-well-350w-36vdc-9-7a-115-230vac-enclosed-switching-power-supply-lrs-350-36). Other power supplies may work, but dimensions and specs may vary — proceed at your own risk if substituting.

This particular power supply can be used with one or two pedals.  If you are using three pedals you should use the [600w Power Suppy](https://github.com/chrisjameschamp/DIY-Active-Pedal-Design/tree/main/Design%20Files/600w%20Power%20Supply) instead.

### Print Settings

This enclosure was printed on a Creality K2 Plus, but your settings will vary depending on the printer and material used. Make sure your filament is well-tuned before printing — the enclosure is large and takes time to complete.

**⚠️ Note:** The main body of the enclosure is just over **280mm wide** and may not fit on most printers. I’ve included a split version that should work on smaller beds. I haven’t tested it personally, but it should print the same.

#### Recommended Print Settings

- **Wall loops**: At least 4
- **Top layers**: 5
- **Bottom layers**: 4
- **Infill**: 20% sparse gyroid
- **If using rectangular infill**: Use 30% or higher

⚠️ **For nylon:**  
Make sure to dry your filament thoroughly before printing. Even slightly damp nylon can result in poor print quality, weak layer bonding, and rough surfaces.

For bed adhesion, use a 10mm brim and optionally apply glue stick or another adhesive. I used both, and they were essential to prevent warping.

## Hardware

The hardware I used can mostly be sourced from [McMaster-Carr](https://www.mcmaster.com/).  
If you're substituting parts from your local hardware store or Amazon, be sure to double-check dimensions — they’re critical for proper fit and function.

### Hardware List

| **Item**                        | **Part Number** | **Qty** | **Link** |
|---------------------------------|-----------------|---------|----------|
| MEANWELL LRS-350-36             | N/A             | 1       | [Link](https://www.omc-stepperonline.com/lrs-350-36-mean-well-350w-36vdc-9-7a-115-230vac-enclosed-switching-power-supply-lrs-350-36) |
| IEC Connector with Power Switch | 5428N118        | 1       | [Link](https://www.mcmaster.com/5428N118/) |
| M3x0.5mm Heat Set Insert        | 94180A333       | 6       | [Link](https://www.mcmaster.com/94180a333/) |
| M3x0.5 14mm Flat Head Screw     | 92125A133       | 4       | [Link](https://www.mcmaster.com/92125A133/) |
| M3x0.5 18mm Flat Head Screw     | 92125A135       | 2       | [Link](https://www.mcmaster.com/92125A135/) |
| M4x0.7 10mm Flat Head Screw     | 92125A190       | 8       | [Link](https://www.mcmaster.com/92125A190/) |
| 6 Pin PCIe Extension Cable      | N/A             | 2       | [Link](https://a.co/d/cVutRBN) |

### Notes

1. **M4 Flat Head Screws** – These should not be longer than 10mm; anything longer could damage the unit.
2. **PCIe Extension Cables** – The full pedal setup requires a total of **6** cables. You’ll need 3 for the PSU and 3 for the pedals, so plan your order accordingly.

## Assembly

A complete walkthrough of the assembly process can be found on the [Wiki](https://github.com/chrisjameschamp/DIY-Active-Pedal-Design/wiki/3-%E2%80%90-PSU-Assembly)

## License

These 3D design files are licensed under a [Creative Commons BY-NC-SA 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

You may:
- Use and remix these files for **personal, non-commercial purposes**.
- Share modified versions, as long as they are also non-commercial, include credit, and use the **same license**.

You may NOT:
- Use these files or derivatives **for commercial use**.
- Re-license modified versions under more restrictive or proprietary terms.

Please credit **@ChrisJamesChamp** and link back to this repository if you use, remix, or share these designs.
