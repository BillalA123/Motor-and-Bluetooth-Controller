# Motor and Bluetooth Controller PCB

Motor control and handheld controller hardware developed for an educational robot at KiP Robotics. Both boards were combined into a single 2-in-1 PCB so they could be fabricated together and snapped apart after manufacturing. This results in a lower cost to make it more accessible to students.

## PCB

<p align="center">
  <img src="Images/KiP%20Controller%2BMotor%20handheld.jpeg" width="90%" alt="Motor and Bluetooth Controller PCB">
</p>

## Schematic

<p align="center">
  <img src="Images/schematic.png" width="100%" alt="Motor and Bluetooth Controller Schematic">
</p>

## Overview

This design combines two separate PCBs: a motor control board and a handheld controller board.

The motor control board handles power distribution and drives four motors, while the controller board allows the user to interface with the robot through a joystick, buttons, and haptic feedback.

### Motor Control Board

- Raspberry Pi Pico based control.
- Two motor driver ICs for controlling up to four motors.
- 5V buck converter for onboard power regulation.
- Terminal Blocks for four motors.
- Connections for two I2C LED screens.
- Additional power and GPIO headers for expansion.

### Bluetooth Controller Board

- Raspberry Pi Pico based controller.
- Analog Joystick for robot control.
- Four push buttons.
- Vibration motor for haptic feedback.
- Bluetooth communication with the motor control board.

## Cost Saving Design

The motor control board and Bluetooth controller board were designed together as a single breakaway PCB. Components were selected with cost as the primary consideration, with effort taken to minimize cost by reducing part count when possible.
