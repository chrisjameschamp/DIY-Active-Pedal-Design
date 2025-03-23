<h2 align="center">DIY Active Pedal Design - Pedal Arm</h2>
<div align="center">
  <img width="800" alt="Header" src="https://github.com/chrisjameschamp/DIY-Active-Pedal-Design/blob/main/Images/Champ_PedalSet_1_V1.png">
</div>

## Index

- [Design](#design)
- [3D Printing](#3d-printing)
   - [Material Options](#material-options)
   - [Print Settings](#print-settings)
- [Hardware](#hardware)
- [Assembly](#assembly)
- [License](#license)

## Design

This is the second design iteration of the Pedal Arm. The first version had mounting brackets approximately 25mm lower, which increased travel but reduced usable servo force. Since that much travel isn’t necessary, I moved the brackets upward — nearly doubling the effective braking force the servos can handle.

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

The hardware I used can almost all be sourced from [McMaster-Carr](https://www.mcmaster.com/), which I know can be a little pricey at times, so if you are swapping out individual hardware from your local hardware store, or Amazon, etc.  Double check dimensions as they are critical for the overall assembly, fitment, and strength of the part.

| **Item**                  | **Part Number** | **Quantity** | **Description**           | **Link**                            | **Notes**                                                                                                                                                                 |
|---------------------------|-----------------|--------------|---------------------------|-------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| M8x1.25 25mm              | 92855A722       | 2            | Low-Proflie Socket Head   | https://www.mcmaster.com/92855A722/ | I did not actually use this exact bolt, I designed for it, but it ended up being quite costly, so I substituted it for a Pan Head bolt of the same specs.                 |
| M8 Nylon Locking Nut      | 93625A300       | 2            |                           | https://www.mcmaster.com/93625A300/ |                                                                                                                                                                           |
| M5x0.8mm Heat Set Insert  | 94180A363       | 2            |                           | https://www.mcmaster.com/94180A363/ |                                                                                                                                                                           |
| M5x0.8 16mm               | 92125A212       | 2            | Hex Drive Flat Head Screw | https://www.mcmaster.com/92125A212/ |                                                                                                                                                                           |
| M5 Steel Finish Washer    |  98472A300      | 2            |                           | https://www.mcmaster.com/98472A300/ |                                                                                                                                                                           |
| M5x0.8 12mm               | 92125A210       | 2            | Hex Drive Flat Head Screw | https://www.mcmaster.com/92125A210/ |                                                                                                                                                                           |
| 8mm OD 4.2mm ID 30mm Long | 92871A212       | 1            | Unthreaded Spacer         | https://www.mcmaster.com/92871A212/ | This will need to be tapped each side for M5x0.8 threads                                                                                                                   |
| M5x0.8 16mm               |                 | 4            | Binding Post Screws       | https://a.co/d/4SsfVXW              |                                                                                                                                                                           |
| M6 Flat Washer            | 93475A250       | 4            |                           | https://www.mcmaster.com/93475A250/ |                                                                                                                                                                           |
| M5x0.8 25mm               | 93805A293       | 2            | Threaded Rod              | https://www.mcmaster.com/93805A293/ | Depending on the Binding Post screw thread depth, you may need to get a shorter variant, however these worked successfully for me with the Bind Post screws listed above. |

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