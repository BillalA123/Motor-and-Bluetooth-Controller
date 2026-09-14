# Motor and Bluetooth Controller PCB

Motor control and handheld controller hardware developed for an educational robot at KiP Robotics, with the goal of making STEM more accessible to students.

## PCB

<p align="center">
  <img src="Images/Screenshot%202026-09-13%192452.png" width="90%" alt="Motor and Controller PCB">
</p>
 
## Overview

This design combines two separate PCBs: a motor control board and a handheld controller board.

The motor control board handles power regulation and drives four motors, while the controller board provides the user interface through a joystick, buttons, and haptic feedback.

### Motor Control Board

- Raspberry Pi Pico based control.
- Two motor driver ICs for controlling up to four motors.
- 5 V buck converter for onboard power regulation.
- Connections for four motors.
- Connections for two LED screens.
- Additional power and GPIO headers for expansion.

### Controller Board

- Raspberry Pi Pico based controller.
- Joystick input for robot control.
- Four user input buttons.
- Vibration motor for haptic feedback.
- Designed to interface with the motor control system.

## Cost Focused Design

The motor control board and controller board were designed together as a single breakaway PCB. The two boards are connected during fabrication and can be snapped apart after manufacturing.

Combining both boards into one fabrication layout was done to reduce manufacturing overhead and make better use of PCB material. Reducing the cost of the electronics was especially important because this hardware is part of an educational robot designed to make STEM learning more accessible to kids.

## Schematic

<p align="center">
  <img src="Images/Job2%20(4)-1.png" width="100%" alt="Motor and Controller PCB Schematic">
</p>

## KiP Robotics

This PCB was developed as part of my work at KiP Robotics, where I led hardware design for a team developing an educational robot focused on making STEM learning more accessible.
