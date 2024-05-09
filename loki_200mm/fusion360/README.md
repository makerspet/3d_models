# Maker's Pet Loki - Fusion360 Design

Open source, very-low-cost 3D-printed ROS2 pet robot. Feel free to modify as you need.

## How to Open Fusion 360 Design
- navigate to [Autodesk](https://www.autodesk.com/products/fusion-360/personal)
  - get a free Fusion 360 license for personal use. As of 2024, the personal license has a limited functionality, but that's OK for this design.
  - or get a free fully-functional trial license
- install Autodesk Fusion 360
- download the latest Loki v???.f3z file from this folder
- launch Fusion 360; File -> Open -> Open From My Computer -> Loki v???.f3z
- File -> Save the imported design into Autodesk cloud
  - Fusion 360 stores designs in its cloud, not as files on your PC
  - next time you need to open the Loki design, use the "Data Panel" on the left in Fusion 360 to browse to your saved Loki design. Double-click the Loki design to open it.
  - if you do not see the Fusion 360 "Data Panel" on the left, click the toolbar 3x3 dots icon at the top to reveal the "Data Panel"

## How to Export STL/3MF for 3D Printing
- open a Loki design (see instructions above)
- use the Browser component tree (inside the opened design window, to the left) to expand the component you need to export, then expand the Bodies folder. For example, Loki -> Caster Wheel -> Bodies
- Right-click on the body you want to export (for example "Caster wheel"), click "Save as mesh".
- Select "Format" 3MF or binary STL. Set unit type millimeter. Expand "Refinement Options". Drag "Surface Deviation", "Normal Deviation" all the way to the left to maximize the resolution. Drag "Maximum Edge Length", "Aspect Ratio" all the way to the right. Click OK and follow prompts to save the file. Fusion 360 may take some time to generate STL/3MF.

## Release History
### v669
- YDLIDAR X2L plate
- YDLIDAR X2 plate
- YDLIDAR X3 PRO plate
- Neato XV11 plate
- RPLIDAR A1 plate
- LDS02RR plate
- ESP32 breakout PCB model
- ESP32 breakout PCB enclosure
- Pico head PCB model

### v550
- brought handset forward by 7mm to improve center of gravity position
- shorter handset upper clamp to remove the handset without undoing the clamp
- upper plate handset stops to prevent the handset sliding out
- lowered the handset's upper clamp to accomodate smaller handsets

### v533 beta release
