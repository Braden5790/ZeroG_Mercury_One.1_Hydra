# ZeroG Mercury One.1 Hydra
Welcome to the configuration repository for my **Ender 5 Pro** that I converted to a **ZeroG Mercury One.1 Hydra 3D Printer**! This repository contains all the configuration files, macros, and scripts needed to run my custom setup powered by [Klipper firmware](https://www.klipper3d.org/).

The folder titled **Printer_Klipper_Configs** contains all of the configuration files that I am currently running on my 3D Printer. Most of my printer was inspired by the stock ZeroG build, except the toolhead where I use the Voron Stealthburner.

---

## Custom Changes
- I wanted to add a nozzle wiper to my printer so I designed a nozzle wiper. This is inspired by the Bambu Lab X1 Carbon poop chute using the A1 wiper. The macro for it can be found in `macros.cfg`.

[Watch the video](./Custom_Changes/ZeroG_Wiper_+_Poop_Chute/Nozzle_Wipe.mp4)


- Created a gusset plate for the top of my printer so I could remove the top front bar and maintain some rigidity.

---

## Contents of Note

- `Custom_Changes`: Folder containing all of the custom 3D Printed parts that I used for this build.
- `printer.cfg`: Main configuration file for the printer.
- `macros.cfg`: Custom macros to enhance functionality.
- `KAMP_Settings.cfg`: [Klipper Adaptive Meshing & Purging](https://github.com/kyleisah/Klipper-Adaptive-Meshing-Purging)

---

## Features

- **Mercury One.1 CoreXY Design**: Optimized for high-speed and high-accuracy printing.
- **Hydra Bed System**: Voron Trident style bed motion system.
- **Klipper Firmware**: Advanced firmware with macro scripting and precise control.
- **Custom Macros**: Streamlined commands for easy operation.
- **Tuned Profiles**: Configurations optimized for my setup, including PID tuning and pressure advance.

---

## Notes

These configurations are specific to my hardware setup and may need adjustments for your build. Refer to the Klipper documentation for detailed information on configuration options.

---

## Acknowledgements

Thanks to the ZeroG team for their incredible design and thanks to the Klipper community for their support.
