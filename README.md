# Smart Street Light System
The Smart Street Light System is an innovative approach to improving energy efficiency in urban lighting infrastructure. Conventional street lighting systems remain powered throughout the night, often wasting energy when no one is present or when ambient light levels are sufficient. This project utilizes a combination of Arduino microcontroller, LDR (Light Dependent Resistor), and PIR (Passive Infrared) sensors to automatically control street lights based on real-time environmental conditions and human activity. The system conserves energy by turning on lights only when necessary, significantly reducing power consumption in low-traffic areas and promoting sustainability.

# Overview
This project demonstrates a Smart Street Light System designed using Arduino IDE and simulated in Proteus 8 Professional. The system automatically controls street lighting based on real-time ambient light conditions and motion detection, providing an energy-efficient solution for urban environments. This project is ideal for IoT and home automation applications.

# Features
𝗔𝘂𝘁𝗼𝗺𝗮𝘁𝗶𝗰 𝗟𝗶𝗴𝗵𝘁 𝗖𝗼𝗻𝘁𝗿𝗼𝗹: Street lights turn on/off based on surrounding light intensity using an LDR (Light Dependent Resistor).

𝗠𝗼𝘁𝗶𝗼𝗻 𝗗𝗲𝘁𝗲𝗰𝘁𝗶𝗼𝗻: Lights activate when motion is detected by a PIR (Passive Infrared) sensor, ensuring lights are only on when needed.

𝗘𝗻𝗲𝗿𝗴𝘆 𝗘𝗳𝗳𝗶𝗰𝗶𝗲𝗻𝗰𝘆: Reduces energy consumption by switching off lights during the day and turning them on only when necessary.

𝗦𝗶𝗺𝘂𝗹𝗮𝘁𝗶𝗼𝗻 𝗦𝘂𝗽𝗽𝗼𝗿𝘁: Full support for simulation using Proteus 8 Professional, enabling easy testing and validation of the design.

 𝗔𝗿𝗱𝘂𝗶𝗻𝗼-𝗕𝗮𝘀𝗲𝗱 𝗗𝗲𝘀𝗶𝗴𝗻: Easy-to-program and highly customizable using the Arduino IDE.

# Components Used
𝗔𝗿𝗱𝘂𝗶𝗻𝗼 𝗨𝗻𝗼: Microcontroller used to control the system.

𝗟𝗗𝗥 𝗦𝗲𝗻𝘀𝗼𝗿: For detecting ambient light conditions.

𝗣𝗜𝗥 𝗦𝗲𝗻𝘀𝗼𝗿: To detect motion and trigger the lights.

𝗟𝗘𝗗𝘀/𝗕𝘂𝗹𝗯𝘀: Representing street lights.

𝗥𝗲𝘀𝗶𝘀𝘁𝗼𝗿𝘀 𝗮𝗻𝗱 𝗪𝗶𝗿𝗲𝘀: Standard electronic components.

𝗣𝗿𝗼𝘁𝗲𝘂𝘀 𝟴 𝗣𝗿𝗼𝗳𝗲𝘀𝘀𝗶𝗼𝗻𝗮𝗹: Used for simulating the circuit.

# Working Principle
𝗗𝗮𝘆 𝗠𝗼𝗱𝗲: During the day or when sufficient ambient light is detected, the street lights remain off.

𝗡𝗶𝗴𝗵𝘁 𝗠𝗼𝗱𝗲: When the light level falls below a certain threshold (detected by the LDR), the system enters night mode, and the lights are turned on if motion is detected by the PIR sensor.

𝗡𝗼 𝗠𝗼𝘁𝗶𝗼𝗻: If no motion is detected, the street lights remain off even in the night mode, conserving energy.

# Setup and Simulation
Arduino IDE
1. Install the Arduino IDE from Arduino's official website.
2. Open the https://github.com/sanyamagarwal10/Smart-Street-Light/blob/main/sketch_may04a.ino  file in the Arduino IDE.
3. Upload the code to the Arduino Uno.

 Proteus 8 Professional
1. Open Proteus 8 Professional.
2. Load the provided smart_street_light.pdsprj file.
3. Run the simulation to test the smart street light system.

# Customization
-> You can adjust the LDR threshold to control the light sensitivity by modifying the Arduino code.

-> Similarly, you can configure the PIR sensor's sensitivity and response time to meet your requirements.
