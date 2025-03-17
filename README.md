# os-auv-electrical-subsystem
Open Source AUV Electrical Subsystem, developed by Robert Fudge 2024-2025

## Introduction
This project was undertaken to support my Universities Capstone Team, with the aim of producing a cost-effective small Autonomous Underwater Vehicle for research purposes. The project is composed of a colaborative effort to design an open-source dataset and model for detection of hazardous physcial landforms. The above design is supported by an open-source interior chassis and an associated electrical subsystem.

The contained electrical design schematics, videos, and physical assembly were completed by Robert Fudge as contribution to this project.

## Use
Our capstone team has agreed to open-source the efforts of our development, under the Apache 2.0 License. If using this project for any academic work, please use the associated BibTeX file for proper citation. Any additions, contributions, or suggestions would be greatly appreciated :)

## Design Flaws
- Ideally the motor propulsion susbystem should have a separate power management subsystem, with its own dedicated power supply. This would provide further seperation between the systems, and allow for potential future modifications, such as a lower power drifting mode, where the system drastically reduces its power consumption and attempts to travel passively through flowing water.
- It would also allow for the computer system to detect issues with propulsion, and plan and execute recovery behavior, such as deploying a rapidly decomposing, triggered solid substance in a variable volume chamber, which would then inflate to increase buoyancy, allowing the device to rise in the water column.

## Planned Future Steps
- Implement an electrical servo system into the design, allowing for the addition of control surfaces.
- Develop a properly shaped hull, optimize for lowered drag coefficient and pressure resistance using Finite Element Analysis (FEA)
- Use the results of the FEA to iterate model design, multiple revisits to the above step may be needed.
- Once an established design, model, and FEA exists

## Parts List
- 2x Blue Robotics T200 Thruster
- 2x BLHeli Electrical Speed Controller
- 1x Mateksys FCHUB 12S
- 1x Pixhawk PX4
- 1x Jetson Orin NX 8GB

## Media
![System startup](https://raw.githubusercontent.com/rnfudge02/os-auv-electrical-subsystem/main/resources/potential_servo_integration.jpeg)
![System startup](https://raw.githubusercontent.com/rnfudge02/os-auv-electrical-subsystem/main/resources/system_init.mp4)