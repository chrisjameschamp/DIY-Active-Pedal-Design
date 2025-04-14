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

This power supply enclosure is completely optional to build, but it adds a few nice features: it hides the power connections, includes a power switch, and uses a standardized cable configuration that’s safe and easy to work with.

The enclosure is built around the [MEANWELL LRS-600-36](https://www.omc-stepperonline.com/lrs-600-36-mean-well-597-6w-36vdc-16-6a-115-230vac-enclosed-switching-power-supply-lrs-600-36). Other power supplies may work, but dimensions and specs may vary — proceed at your own risk if substituting.

## 3D Printing

The enclosure is designed to be 3D printed. While it could be CNC machined, that approach would likely be more expensive and complex. If you do machine it, you could simplify the design in several areas (e.g., using drill taps instead of hardware).

### Material Options

I’ve only tested this part using eSun’s [ePA-CF](https://a.co/d/0XDH10W), an 80/20 nylon-carbon fiber composite. It offers great strength, layer adhesion, and added rigidity from the carbon. It also has relatively high tensile strength.

That said, strength isn’t as critical for this part compared to others in the pedal system. More affordable options like PETG+CF or ABS+CF may actually be preferable here — they’re easier to print and still provide sufficient durability.

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
| MEANWELL LRS-600-36             | N/A             | 1       | [Link](https://www.omc-stepperonline.com/lrs-600-36-mean-well-597-6w-36vdc-16-6a-115-230vac-enclosed-switching-power-supply-lrs-600-36) |
| IEC Connector with Power Switch | 5428N111        | 1       | [Link](https://www.mcmaster.com/5428N111/) |
| M3x0.5mm Heat Set Insert        | 94180A333       | 6       | [Link](https://www.mcmaster.com/94180a333/) |
| M3x0.5 14mm Flat Head Screw     | 92125A133       | 4       | [Link](https://www.mcmaster.com/92125A133/) |
| M3x0.5 18mm Flat Head Screw     | 92125A135       | 2       | [Link](https://www.mcmaster.com/92125A135/) |
| M4x0.7 10mm Flat Head Screw     | 92125A190       | 10      | [Link](https://www.mcmaster.com/92125A190/) |
| 6 Pin PCIe Extension Cable      | N/A             | 3       | [Link](https://a.co/d/cVutRBN) |

### Notes

1. **M4 Flat Head Screws** – These should not be longer than 10mm; anything longer could damage the unit.
2. **PCIe Extension Cables** – The full pedal setup requires a total of **6** cables. You’ll need 3 for the PSU and 3 for the pedals, so plan your order accordingly.

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