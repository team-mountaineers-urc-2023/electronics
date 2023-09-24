# Payload PCB v3.1

## Overview
The Payload PCB is used to control the electronics on the manipulator and the science payload. It can control up to eight DC motors and twelve servos. It also includes the hardware necessary for CAN bus communication, extra I/O connectors, payload select signals, and a USB2CAN converter.

## Features
- 4-layer board
- Raspberry Pi Pico microcontroller
- 4 DRV8874 H-bridge motor driver breakout boards capable of controlling 12V motors
- 2 TB6612FNG motor driver breakout boards that can each control two 12V motors or one stepper motor
- Capable of controlling up to twelve servo motors with selectable power output
- Hardware for CAN bus communication
- Optional place to put a 16th brick 12V regulator to power the board and payload motors
- 17 I/O connectors with GPIO, PWM, and/or analog input capabilities
- Payload select pins and LEDS to indicate which payload is plugged in
- Integrated USB2CAN converter which allows the computer to connect to the CAN bus using a USB connection
- Reverse polarity protection

## Contributors
- [Zach Waddell](https://github.com/zmw0006)

- [Ronald Butts](https://github.com/rmb0034)

- [Kendra Gillo](https://github.com/kgillo)

![Picture of Payload PCB](https://github.com/team-mountaineers-urc-2023/electronics/blob/main/PCB%20Files/Payload%20PCB%20v3.1/Documentation/Payload_PCB_v3.1.png)
