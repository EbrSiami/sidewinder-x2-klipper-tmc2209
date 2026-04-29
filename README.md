# Artillery Sidewinder X2 - Klipper Configuration (TMC2209 Mod)

## i have to add files one by one duo to the internet limitations here and i can't upload anything in any way

This repository contains my personal Klipper configuration for the **Artillery Sidewinder X2**. 

**Note:** This configuration is specifically tuned for a printer that has been upgraded with **TMC2209 stepper drivers**. If you are using the stock drivers, you may need to adjust the current and pin settings plus turning off the UART.

I have also connected drivers via UART for more controll

## Features:
- **Stepper Drivers:** Configured for TMC2209 (Silent & Cool).
- **Input Shaper:** Pre-configured (tuned via ADXL345) to reduce ringing at high speeds.
- **Bed Leveling:** Optimized Bed Mesh and Screws Tilt Adjust.
- **Macros:** Includes standard Start/End G-code, Pause/Resume, and Filament Change.
- **Pressure Advance:** Calibrated with stock extruder.
- **KAMP:** For better first layer

## Hardware Specifications:
- **Printer:** Artillery Sidewinder X2
- **Mainboard:** Stock ruby 1.2
- **Drivers:** 2x TMC2209 for X and Y axix and z axis using one stock fs31w01 in Series
  also extruder is same fs31w01 (which i think that its a clone of TMC2100) 
- **Firmware:** Klipper

in my case the maximum stable speed for this printer is around 210mm/s and around 4/5000mm/s acceleration

for drivers you just need to connect the RX pin of tmc2209 to one of the free pins in EXT1 port
 i connected the first driver (X Axis) to PB4 and Y axis to PB3

Im using the **Orange Pi 3B** for Klipper with Ubuntu server 22.04 LTS and it works well so far (around 1 year)

i'll upload more data such as my device and input shape pictures soon if i can

##Thank you for your Attention to this matter! 
  Ebrahim .GH Siami
