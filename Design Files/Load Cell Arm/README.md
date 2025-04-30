<h2 align="center">DIY Active Pedal Design - Load Cell Arm</h2>
<div align="center">
  <img width="800" alt="Header" src="https://github.com/chrisjameschamp/DIY-Active-Pedal-Design/blob/main/Design%20Files/Load%20Cell%20Arm/Images/Champ_Load_Cell_Arm_V1.png">
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

The load cell arm connects the pedal arm to the slider and is the primary component for transferring forces between the pedal arm and the servo motor.

## 3D Printing

The arm is designed to be 3D printed, though it is one of the few parts that would **greatly benefit** from being CNC machined due to the forces involved.

### Material Options

This part has only been tested using [Fiberon's PPS-CF](https://a.co/d/0nK6oxm).

While PPS is known for its **high temperature resistance**, it also offers excellent stiffness with minimal deformation, making it ideal for this application. Nylon may work, but it tends to flex more under load. Less deformation in this part means more accurate and precise force transfer to the load cell.

### Print Settings

The arm was printed on a Creality K2 Plus, but settings may vary depending on your printer and chosen material.

#### Recommended Print Settings

- **Wall loops**: At least 10
- **Top layers**: 12
- **Bottom layers**: 10
- **Infill**: 30% sparse gyroid
- **If using rectangular infill**: Use 40% or higher

⚠️ For PPS:
Thoroughly dry your filament before printing. Even slightly damp PPS will print poorly, resulting in weak layer adhesion and rough surface quality.

## Hardware

The hardware I used can mostly be sourced from [McMaster-Carr](https://www.mcmaster.com/).  
If you're substituting parts from your local hardware store or Amazon, be sure to double-check dimensions — they're critical for fit and function.

### Hardware List

| **Item**                        | **Part Number** | **Qty** | **Link** |
|---------------------------------|-----------------|---------|----------|
| Pressure Sensor S Load Cell Weight Sensor(200KG) | DYLY-107 | 1 | [Link](https://a.co/d/eEIK39s) |
| M8.5x1.25 18mm Cap Head Screw   | 91292A080       | 2       | [Link](https://www.mcmaster.com/91292A080/) |
| 608ZZ Bearing                   | 608ZZ           | 4       | [Link](https://a.co/d/8xCCTFy) |

### Notes

1. **Pressure Sensor** – I used the 200KG variant, which is the highest recommended. Anything between 100KG and 200KG should work well depending on your force preference.

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