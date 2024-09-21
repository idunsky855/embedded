# Embedded-exp2: PIC32MX370F512L Kit Project

## Overview
This project implements various LED control and interaction features using the PIC32MX370F512L microcontroller kit. It demonstrates different LED patterns, user input handling through switches, and audio output capabilities.

## Features
The project includes the following functionalities, controlled by switches:

1. **Switch 00**: Binary counter - LED
2. **Switch 01**: Shift - LED
3. **Switch 02**: Swing - LED
4. **Switch 03**: Direction control - up/down - right/left
5. **Switch 04**: Speed control - fast/slow
6. **Switch 05**: Halt
7. **Switch 06**: Beep - speaker
8. **Switch 07**: Exit

## Priority
The project implements a priority system for LED control modes:
- Switch 02 (Swing) > Switch 01 (Shift) > Switch 00 (Binary counter)

## Example
[![YouTube video example](https://img.youtube.com/vi/CioAtJIJ23Y/0.jpg)](https://www.youtube.com/watch?v=CioAtJIJ23Y)

## Hardware Requirements
- PIC32MX370F512L microcontroller kit
- LEDs
- Speaker
- Switches

## Software Requirements
- MPLAB X IDE 
- XC32 Compiler

## Setup and Usage
1. Clone the repository
2. Open the project in MPLAB X IDE
3. Compile and upload the code to the PIC32MX370F512L kit
4. Use the switches to control different functionalities

## Function Descriptions

### Binary Counter (Switch 00)
Implements a binary counting sequence on the LEDs.

### Shift (Switch 01)
Creates a shifting pattern on the LEDs.

### Swing (Switch 02)
Produces a swinging effect on the LED display.

### Direction Control (Switch 03)
Changes the direction of LED patterns (up/down or right/left).

### Speed Control (Switch 04)
Adjusts the speed of LED patterns (fast/slow).

### Halt (Switch 05)
Pauses the current LED pattern.

### Beep (Switch 06)
Activates the speaker to produce a beep sound.

### Exit (Switch 07)
Exits the current operation or resets the system.

## Future Enhancements
- Additional LED patterns
- Integration with other sensors or outputs
- Implementing a user interface for remote control

## Contributors
Idan Dunsky
Yaniv Kaveh-Shtul

