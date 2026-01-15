# DIY-Gimbal-based-Sim-Racing-Handbrake
This repository serves as guide to building a DIY USB handbrake for sim racing by repurposing an old flight joystick and programming a microcontroller for computer interface. 

The device simulates a hydraulic handbrake with a variable analog axis, which can be mapped in racing games such as Assetto Corsa, BeamNG.drive, and iRacing. This is a great project if you have unused hardware and want a relatively inexpensive handbrake for starting out your sim racing journey.

## Hardware requirements
- Any old flight joystick with a potentiometer-based gimbal (I used a Logitech Freedom 2.4)
- STM32F407G-DISC1 microcontroller board
- Male mini-USB type-B to Male USB type-A cable
- Male micro-USB type-B to Male USB type-A cable
- Female-to-female breadboard jumper wires (Alternatively, standard copper wires can be used if you have access to a soldering kit)
#### NOTE: Both cables need to have data transfer functionality.

## Software requirements
- STM32CubeIDE for programming the microcontroller
#### NOTE: It is recommended to use version 1.19.0 of STM32CubeIDE or older, as STM32CubeMX and ST-MCU-FINDER-PC are detached from later versions. These components are required and will have to be installed seperately if you decide to utilize a later version.
