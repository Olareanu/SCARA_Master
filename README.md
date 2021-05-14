# SCARA_Master

This is the main repository for Olăreanu Alexandru's educational SCARA Robot.
You can find documentation in the "SCARA-Robot_Doc_RO" file.

Source code is available in this repository: [SCARA-Commander](https://github.com/Olareanu/SCARA-Commander)

Information about the Hardware (both electronics and mechanical design) can be found in this repository: [SCARA-Hardware](https://github.com/Olareanu/SCARA-Hardware)

## Introduction
SCARA stands for Selective Compliance Articulated Robotic Arm. Such arms usually have multiple segments linked one after the other to facilitate movement on X and Y axes and an additional Z axis perpendicular to those (although many types of geometries exist.)

The aim of this project is to design, build and program a 2 axis SCARA Robot. The robot should be controlled trough standard Gcode sent from a computer.

The electronics are custom designed and manufactured with easyEDA and JLCPCB with additional parts from Mouser Electronics. Most of the Hardware is 3D printed, some parts sourced locally. Stepper Motors from StepperOnline. The code runs on an STM32F411CE Black Pill Microcontroller and is compiled using PlatformIO in CLion. The C++ programming language is used.

## References
Here are some usefull links:
[SCARA Wikipedia Page](https://en.wikipedia.org/wiki/G-code)
[Gcode Wikipedia Page](https://en.wikipedia.org/wiki/G-code)
[PlatformIO](https://platformio.org/)

## Contributing
This project was made by Olăreanu Alexandru.

## License
The Code is under GPLv3 License. Please ask permission for the use of the Hardware. Working with electronics is dangerous. Olăreanu Alexandru is not responsible for liabilities.