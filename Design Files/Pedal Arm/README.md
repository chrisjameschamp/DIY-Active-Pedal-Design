<h2 align="center">DIY Active Pedal Design - Pedal Arm</h2>
<div align="center">
  <img width="800" alt="Header" src="https://github.com/chrisjameschamp/DIY-Active-Pedal-Design/blob/main/Design%20Files/Pedal%20Arm/Images/Champ_PedalArm_V3.png">
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

This is the third design iteration of the Pedal Arm. The first version had mounting brackets approximately 25mm lower, which increased travel but reduced usable servo force. Since that much travel isn’t necessary, the brackets were moved upward in later revisions — nearly doubling the effective braking force the servos can handle. The current version also includes additional stiffness improvements over the earlier arms.

## 3D Printing

The arm is designed to be 3d printed, it could be CNC machined as well, although it would probably not be super easy and/or cheap.  If it were to be CNC machined however, there are a lot of areas that could be simplified or adjusted with drill taps to eliminate the use of some hardware.

### Material Options

I’ve only tested this part printed in eSun’s [ePA-CF](https://a.co/d/0XDH10W), an 80/20 nylon-carbon fiber composite with excellent strength, layer adhesion, and added rigidity from the carbon fiber. It also has relatively high tensile strength.

You could try pure nylon, although it might be too flexible.

More affordable options like PETG+CF or ABS+CF composites may work as well. While they likely have enough strength in the XY axis (which is how the part is oriented for printing), I’m less confident in their Z-axis strength due to weaker layer bonding.

Some users in the DIY FFB Pedal Discord have reported success with PLA+ or regular PETG. I haven’t tested these myself, and I’d be cautious about PLA+’s long-term durability.

### Print Settings

The pedal arm was printed on a Creality K2 Plus, but print settings will vary depending on your printer and material. Make sure your filament and printer are well-tuned before attempting a full print — it’s a large part and can take quite a while.

Don’t do what I did and print seven of them while dialing in settings 😅

#### Recommended Print Settings

- **Wall loops**: At least 10
- **Top layers**: 12
- **Bottom layers**: 10
- **Infill**: 30% sparse gyroid
- **If using rectangular infill**: Use 40% or higher

⚠️ For nylon:
Thoroughly dry your filament before printing. Even slightly damp nylon will print poorly, resulting in weak layer adhesion and rough surface quality.

Due to the high wall/infill density, use a brim (10mm recommended) and possibly glue stick or other adhesion aid. I used both, and they were necessary to prevent warping.

## Hardware

The hardware I used can mostly be sourced from [McMaster-Carr](https://www.mcmaster.com/).  
If you're substituting parts from your local hardware store or Amazon, be sure to double-check dimensions — they're critical for fit and function.

### Hardware List

| **Item**                        | **Part Number** | **Qty** | **Link** |
|---------------------------------|-----------------|---------|----------|
| M8x1.25 25mm Hex Cap Head Screw | 92095A286       | 2       | [Link](https://www.mcmaster.com/92095A286/) |
| M8 Nylon Locking Nut            | 93625A300       | 2       | [Link](https://www.mcmaster.com/93625A300/) |
| M5x0.8mm Heat Set Insert        | 94180A363       | 6       | [Link](https://www.mcmaster.com/94180A363/) |
| M3 Square Nut                   | 97258A101       | 2       | [Link](https://www.mcmaster.com/97258A101/) |
| M5x0.8 14mm Socket Head Screw   | 91292A058       | 4       | [Link](https://www.mcmaster.com/91292A058/) |
| M3x0.5 16mm Flat Head Screw     | 92125A134       | 2       | [Link](https://www.mcmaster.com/92125A134/) |
| M5x0.8 16mm Flat Head Screw     | 92125A212       | 2       | [Link](https://www.mcmaster.com/92125A212/) |
| M5 Steel Finish Washer          | 98472A300       | 2       | [Link](https://www.mcmaster.com/98472A300/) |
| M5x0.8 12mm Flat Head Screw     | 92125A210       | 2       | [Link](https://www.mcmaster.com/92125A210/) |
| 8mm OD, 4.2mm ID, 30mm Spacer   | 92871A212       | 1       | [Link](https://www.mcmaster.com/92871A212/) |
| 608ZZ Bearing                   | 608ZZ           | 2       | [Link](https://a.co/d/8xCCTFy) |

### Notes

1. **M5x0.8mm Heat Set Insert** – The side mounts use 4 x M5x0.8mm Heat Set Insert. The front-facing holes of the pedal arm use 2 x M5x0.8mm Heat Set Insert.
2. **8mm OD Spacer** – This needs to be **tapped on both sides** for M5x0.8 threads.


## Assembly

Complete walkthroughs of the assembly process can be found on the [Pedal Arm wiki page](https://github.com/chrisjameschamp/DIY-Active-Pedal-Design/wiki/06-%E2%80%90-Pedal-Arm) and [Arm Connection wiki page](https://github.com/chrisjameschamp/DIY-Active-Pedal-Design/wiki/10-%E2%80%90-Arm-Connection).

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
