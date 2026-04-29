# Artillery Sidewinder X2 - Klipper Configuration (TMC2209 Mod)

This repository contains my personal Klipper configuration for the **Artillery Sidewinder X2**. 

⚠️ **Note:** This configuration is specifically tuned for a printer that has been upgraded with **TMC2209 stepper drivers**. If you are using the stock drivers, you may need to adjust the current and pin settings plus turning off the UART.

I have also connected drivers via 

## Features:
- **Stepper Drivers:** Configured for TMC2209 (Silent & Cool).
- **Input Shaper:** Pre-configured (tuned via ADXL345) to reduce ringing at high speeds.
- **Bed Leveling:** Optimized Bed Mesh and Screws Tilt Adjust.
- **Macros:** Includes standard Start/End G-code, Pause/Resume, and Filament Change.
- **Pressure Advance:** Calibrated with stock extruder.

## Hardware Specifications:
- **Printer:** Artillery Sidewinder X2
- **Mainboard:** Stock ruby 1.2
- **Drivers:** 4x TMC2209
- **Firmware:** Klipper

in my case the maximum stable speed for this printer is around 210mm/s and around 4/5000mm/s acceleration

i'll upload more data here in next commits

