# Binary Voltage Indicator

[![CI](https://github.com/Qeteshpony/BinaryVoltageIndicator/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Qeteshpony/BinaryVoltageIndicator/actions/workflows/ci.yml)

![3D Render](https://qeteshpony.github.io/BinaryVoltageIndicator/3D/BinaryVoltageIndicator-3D_top.png)

[Hardware Documentation](https://qeteshpony.github.io/BinaryVoltageIndicator)

A small board that can be attached to a 5V power supply to show if the voltage is above or below 5.0V with a maximum tolerance of about 2% (±0.1V) when 1% resistors are used.

The board can also be directly plugged onto a Raspberry Pi GPIO header to have a quick visual aid about the power supply status. The third pin is an open collector output that pulls down when the voltage is above 5.0V. When plugged onto the GPIO header this gets connected to GPIO14. 

Connections when directly plugged in:

| Board | GPIO Header|
|:------|:-----------|
|  VCC  | 4 (5V)     |
|  GND  | 6 (GND)    |
|  VOK  | 8 (GPIO14) |

When using a cable, VOK can of course be connected to any GPIO Pin or not be used at all. 

The "wings" with the screw holes can be used to mount the board in a case or broken off if they are not needed. 
