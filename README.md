# 🤖 Obstacle Avoiding Robot Vacuum Cleaner Project

## Introduction 🌟
A **robot vacuum**, often referred to as an **obstacle vacuum cleaner**, is a cutting-edge cleaning tool designed to automatically explore and clean floors without human assistance. These machines utilize sensors and artificial intelligence to recognize and avoid obstacles like furniture, walls, and stairs, adjusting their cleaning patterns based on the structure of the area. As technology advances, obstacle vacuum cleaners are becoming increasingly popular for their convenience and time-saving features, allowing homeowners to maintain their floors effortlessly. In today’s tech-driven world, these vacuum cleaners have become a household staple, revolutionizing home cleaning. 

### System Components 🛠️
This project consists of:
- **Two Infrared (IR) Sensors**: One on the right and one on the left.
- **L293D Motor Driver IC**
- **Voltage Converter**
- **Gear DC Motor**

### Working Principle ⚙️
- If the intensity from both sensors is low, the robot identifies an object and moves backward.
- If the right sensor detects low intensity, the robot moves backward and makes a right turn.
- The robot advances until it encounters a barrier if no object is spotted.

## Apparatus List 📝
1. IR Sensor x2
2. Breadboard
3. Motor Driver IC LN293D
4. 10 μF Capacitor
5. Voltage Regulator IC 7805
6. 100k ohm Resistor x2
7. 10k ohm Resistor x2
8. 6v DC Motor
9. Plastic Fan

## Project Description 📋
An **obstacle vacuum cleaner** is a compact, self-contained cleaning device designed to vacuum floors autonomously. It uses sensors to detect and navigate around obstacles like walls, furniture, and stairs while effectively cleaning various surfaces, including hardwood floors, carpets, and tiles. The combination of suction and revolving brushes ensures thorough cleaning.

## About the Parts 🔩
### i) Robotic Casing 🧳
The **robotic casing** protects the internal components of the robot, providing a smooth, aesthetically pleasing exterior and shielding the robot from environmental elements like moisture, dust, and extreme temperatures.

### ii) Power Supply 🔋
We use a 9V power supply with an **18650 lithium-ion rechargeable battery**. Each battery cell has a voltage of 3.7V, and with two parallel cells connected in series, we obtain approximately 9V.

### v) Working of L293D Motor Driver IC 🚗
- **Enable Pins (1-2 & 3-4)**: Control the motor speed.
  - Connected to +5V, the motor runs at maximum speed.
  - Connected to ground, the motor stops.
- **Input Pins (2,7 for Motor A & 10,15 for Motor B)**: Control the direction of motor rotation.
- **Output Pins (3,6 for Motor A & 11,14 for Motor B)**: Provide the motor's output.
- **GND (4, 5, 12, 13)**: Connects to the ground of the power source.
- **VSS2 (Pin 8)**: Power supply positive pin for running motors (4.5V to 36V).
- **VSS1 (Pin 16)**: 5V supply for the IC.

### IC 7805 Voltage Regulator 🔌
- Minimum Input Voltage: 7V
- Maximum Input Voltage: 35V
- Current Rating: 1A
- Maximum Output Voltage: 5.2V
- Minimum Output Voltage: 4.8V

## Hardware Implementation 🔧
### Breadboard Implementation 🧩
All components were initially implemented on a breadboard, and the project was successfully tested and run.

## Full Circuit Diagram 🖼️
An **inverting integrator** is a type of operational amplifier (op-amp) circuit that produces an output voltage proportional to the integral of the input voltage with respect to time, but with an inverted polarity. It is commonly used in analog signal processing applications, such as in audio and instrumentation circuits.

## Results 🏆
1. IR Sensor cannot detect any black object.
2. Can sense objects at a distance of 10 cm.
3. Robot can sense objects with a minimum height of 3 cm from the ground.
4. Robot stops when a 45-degree angle occurs at a corner.
5. At full charge, the robot can run about 0.72 meters per minute.
6. Without obstacles, it outputs 0V.
7. With obstacles, it outputs 3.5V.

## Real Life Applications 🚀
### 1. Robot Vacuum
Automatically detects and avoids obstacles (persons, walls, chairs, tables, etc.) along its path to avoid absorbing dust in its chamber.

### 2. Self-Driving Car 🚗
This car autonomously detects what is in front of it and around it, steering clear of vehicles, people, or other objects on the road. For instance, it is integrated into a Tesla car.

## Conclusion 🎯
This project demonstrates a straightforward and cost-effective robot for detecting obstacles. With IR sensors, the robot effectively avoids obstacles, prevents collisions, and adjusts its path accordingly. The design allows for the addition of more functionalities, enabling it to perform various tasks with minimal human involvement. This technology has potential applications in defense, security, and hostile environments, marking significant progress in these industries.

![Thank You](https://img.shields.io/badge/Thank%20You!-blue?style=flat-square&logo=smile)

<!-- Graphical GIF Animation -->
<div class="gif-container" style="text-align: center; margin-bottom: 20px;">
  <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExYzdob2I4cHdsdWhnbmtmYTBxbnk4cnl2YjZ1bGw5ZGZvMXBwdWc4bSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/00n6TSoGffGTLXSMPO/giphy.gif" alt="Working on it GIF" />
</div>
