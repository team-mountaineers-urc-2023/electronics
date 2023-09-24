# Battery Monitor v1.2

## Overview
The battery monitor was designed for the 2023 rover to monitor its battery usage. The PCB features shunt resistors to measure the current draw from up to four batteries. It can communicate status using an LCD screen or over the rover's CAN bus.

## Features
- 4-layer board
- Raspberry Pi Pico microcontroller
- Measures battery voltage and current using shunt resistors combined with LTC4151 ICs
- Embedded emergency stop circuitry
- Ideal diode circuits to connect batteries in parallel
- Control for an external LCD screen and an LED strip
- Hardware for CAN bus communication
- Reverse polarity protection

## Contributors
- [Kendra Gillo](https://github.com/kgillo)

- [Zach Waddell](https://github.com/zmw0006)

![Picture of Battery Monitor PCB](Documentation\Battery_Monitor_1.2.png)
