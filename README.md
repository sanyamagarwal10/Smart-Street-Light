# Smart Street Light System
The Smart Street Light System is an innovative approach to improving energy efficiency in urban lighting infrastructure. Conventional street lighting systems remain powered throughout the night, often wasting energy when no one is present or when ambient light levels are sufficient. This project utilizes a combination of Arduino microcontroller, LDR (Light Dependent Resistor), and PIR (Passive Infrared) sensors to automatically control street lights based on real-time environmental conditions and human activity. The system conserves energy by turning on lights only when necessary, significantly reducing power consumption in low-traffic areas and promoting sustainability.

# Overview
This project demonstrates a Smart Street Light System designed using Arduino IDE and simulated in Proteus 8 Professional. The system automatically controls street lighting based on real-time ambient light conditions and motion detection, providing an energy-efficient solution for urban environments. This project is ideal for IoT and home automation applications.

# Features
Automatic Light Control: Street lights turn on/off based on surrounding light intensity using an LDR (Light Dependent Resistor).

Motion Detection: Lights activate when motion is detected by a PIR (Passive Infrared) sensor, ensuring lights are only on when needed.

Energy Efficiency: Reduces energy consumption by switching off lights during the day and turning them on only when necessary.

Simulation Support: Full support for simulation using Proteus 8 Professional, enabling easy testing and validation of the design.

Arduino-Based Design: Easy-to-program and highly customizable using the Arduino IDE.

# Components Used
Arduino Uno: Microcontroller used to control the system.
LDR Sensor: For detecting ambient light conditions.
PIR Sensor: To detect motion and trigger the lights.
LEDs/Bulbs: Representing street lights.
Resistors and Wires: Standard electronic components.
Proteus 8 Professional: Used for simulating the circuit.

# Working Principle
Day Mode: During the day or when sufficient ambient light is detected, the street lights remain off.
Night Mode: When the light level falls below a certain threshold (detected by the LDR), the system enters night mode, and the lights are turned on if motion is detected by the PIR sensor.
No Motion: If no motion is detected, the street lights remain off even in the night mode, conserving energy.

