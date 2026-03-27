# Matyas-s-Hackpad
It has 8 keys (7 switches + rotary encoder switch), a rotary encoder, and an OLED display. Each key is backlit with SK6812 MINI-E LEDs. It uses [QMK](https://qmk.fm/) firmware and VIA.

## CAD Model:
Everything is connected by four M3x16mm screws and M3x5mx4mm heatset inserts. The case is printed in two parts, top and bottom.
<p align="center">
  <img src="Assets/CAD.png" alt="Matyas Hackpad" width="500">
</p>
<p align="center">
  <strong>Made in Fusion360</strong>
</p>

## PCB:
<p align="center">
  Schematic
</p>
<p align="center">
  <img src="Assets/Schematic.png" alt="Matyas Hackpad" width="500">
</p>
<br>
<p align="center">
  PCB
</p>
<p align="center">
  <img src="Assets/PCB.png" alt="Matyas Hackpad" width="500">
</p>
<p align="center">
  <strong>Made in KiCad</strong>
</p>

## Case:
<p align="center">
  <img src="Assets/Case.png" alt="Matyas Hackpad" width="500">
</p>
<p align="center">
  <strong>Made in Fusion360</strong>
</p>

## Firmware:
This Hackpad uses [QMK](https://qmk.fm/) firmware. Everything can be controlled in VIA. I have five layers set up, and I can assign anything to each one. I switch between them with a single switch. My layers are Main, Media, HA (shortcuts for Home Assistant), Game, and Other. I can also adjust the effects, speed, brightness, and backlight colors of LEDs directly from VIA. The OLED display shows the name of the current page.

## Final result:
<p align="center">
  <img src="Assets/Hackpad photo.jpg" alt="Matyas Hackpad" width="45%">
  <img src="Assets/Hackpad photo 2.jpg" alt="Matyas Hackpad" width="45%">
</p>

## BOM:
Here is everything you need to create this Hackpad:
| Component | Amount |
| :--- | :---: |
| **Seeed XIAO RP2040** | 1x |
| **MX-Style switches** | 7x |
| **1N4148 Diodes** | 8x | 
| **EC11 Rotary encoder** | 1x |
| **0.91 inch OLED display** | 1x |
| **DSA keycaps** | 7x |
| **SK6812 MINI-E LED** | 7x |
| **M3x16mm screw** | 4x |
| **M3x5mx4mm heatset insert** | 4x |
| **Case** (2 printed parts) | 1x |
| **PCB** | 1x |
