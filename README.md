# Xiao-ESP32-C6-Power-and-MOSFET-Breakout-Board
A compact breakout board for the XIAO ESP32-C6 featuring a dual-MOSFET power switch circuit, dedicated battery input, and screw terminals. Perfect for building battery-powered IoT devices, smart switches, and high-current applications controlled directly by the ESP32.
# XIAO ESP32-C6 Power & I/O Breakout Board (C&S V1.0)

![EasyEDA](https://img.shields.io/badge/Designed_in-EasyEDA-blue)
![License](https://img.shields.io/badge/License-MIT-green)

This repository contains the complete hardware design files for a custom **Power & I/O Breakout Board** for the **Seeed Studio XIAO ESP32-C6**.

This board is not just a generic breakout; it includes an onboard power switching circuit, making it an ideal platform for controlling high-power devices directly from the low-power XIAO ESP32-C6.

![3D Render](images/3d_render.png) <!-- Make sure to place your 3D render image in an 'images/' folder -->

## ✨ Project Overview
----------------------------------
<img width="700" height="501" alt="Schematic_Xiao_esp32c6_2026-05-02" src="https://github.com/user-attachments/assets/68d44d23-32c1-48f3-9f92-0be80d0fa4e5" />

----------------------------------
<img width="726" height="482" alt="Xiao_esp32c6_3D_Top_View" src="https://github.com/user-attachments/assets/586e8efb-de8e-4c31-9844-ab61bc9b392c" />

-----------------------------------
<img width="772" height="462" alt="Xiao_esp32c6_3D_Bottom_View" src="https://github.com/user-attachments/assets/dc89572e-cb8d-47b0-8c97-59a3c20d6147" />

-------------------------------------
<img width="588" height="376" alt="Xiao_esp32c6_2D_View" src="https://github.com/user-attachments/assets/1ba9ed8f-d0b4-4d5b-bc5f-f1fc89507906" />

---------------------------------------
The XIAO ESP32-C6 is a powerful low-power MCU with Wi-Fi 6 and Bluetooth 5.3. This breakout board provides a robust platform to easily connect it to external sensors and power loads:

*   **Onboard Power Switching:** A dual-MOSFET circuit (`IRLML6344`) allows the XIAO's `D2` pin to safely switch an external load connected to the `Drain_1` terminal. This is great for controlling lights, small motors, or other devices.
*   **Flexible Powering:** Includes a dedicated 2-pin screw terminal (`BAT-`) and headers (`+5V`, `GND`) for easy battery or external power connection.
*   **Full Pin Breakout:** All GPIO pins of the XIAO ESP32-C6 are broken out to a standard 10-pin header (`U4`).

## 📂 Repository Structure
```text
/
├── images/                               # PCB renders and screenshots
├── Schematic_Xiao_esp32c6_2026-05-02.pdf # Full circuit schematics
├── PCB_PCB_Xiao_esp32c6_2026-05-02.pdf   # PCB layout visual
├── BOM_Xiao_esp32c6_2026-05-02.csv       # Bill of Materials
└── PickAndPlace_PCB_Xiao_esp32c6_2026-05-02.csv # Pick & Place coordinates
