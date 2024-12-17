# Arduino Leonardo - KiCad 8 Port

This project is a fork of the original [Arduino Leonardo KiCad project](https://github.com/eltorio/leonardo). It has been modified to remove any branding restrictions, making it suitable for use in general projects without concerns about licenses or rebuilding the Bill of Materials (BOM). Footprints have been updated to use components from the KiCad standard library, allowing for the use of some of the cheapest products available on the market. These changes ensure a low-cost BOM. 

> [!NOTE] 
> This repository may not be maintained regularly. I am only doing this for a one-off project, but leaving it here in case it benefits anyone else.

## Overview

The Arduino Leonardo board design has been ported to **KiCad 8**, enabling hobbyists and developers to integrate it into their own projects easily.

## Schematic
![Schematic](https://github.com/eltorio/leonardo/raw/main/schematic.png)  
View the full [schematic PDF](https://github.com/eltorio/leonardo/raw/main/schematic.pdf).

## PCB Layout
![Board](https://github.com/eltorio/leonardo/blob/main/board.png?raw=true)  
The board layout matches the Arduino Leonardo Rev3 design.

- Default silkscreen **hides component references** for compatibility with Leonardo boards.
- Use the [Hide References Plugin](https://github.com/joelsa/kicad-hide-references-plugin) to toggle component visibility.

## 3D Renders
### Without Component References  
![Front without refs](https://raw.githubusercontent.com/eltorio/leonardo/main/board_3d_front.png?raw=true)

### With Component References  
![Front with refs](https://raw.githubusercontent.com/eltorio/leonardo/main/board_3d_front_w_ref.png?raw=true)

## Bill of Materials (BOM)
The project includes a detailed, ready-to-use BOM: [View BOM](https://raw.githubusercontent.com/eltorio/leonardo/main/Leonardo_Rev3e.html).

Key details:
- All parts are readily available.
- Includes part numbers for ordering components from Digi-Key.

## License
This project is licensed under the **Attribution-ShareAlike 4.0 International** ([CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)).  
The original design was ported to Kicad by [eltorio](https://github.com/eltorio/leonardo).