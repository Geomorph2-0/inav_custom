# Notes

This is the first custom target I'm using to test the inav flight controller firmware for my custom flight controller based on the STM32F411CEU6. The target files were obtained from this [github repo ](https://github.com/rizacelik/STM32F411CEU6_INAV_Firmware)and have been tweaked slightly to conform to inav 5.1.0 standards. Upon building this and flashing to firmware, no response is observerd/noticed from my MCU.

## Changes Made

### TARGET.H

In this file, the following changes were made:

Line 107

Line 108

Line 126

Line 131

I may still make changes to line 106. I'm still not sure as to the reason the built firmware is not responding on the MCU after flashing, but the investigation continues.

### TARGET.C

In this file, the following changes were made:

Line 30-35: TIM_USE_OUTPUT_AUTO changed to TIM_USE_MC_MOTOR.
