# Automated-Vacuum-cleaner
Automated Vacuum Cleaner
An innovative robotic vacuum cleaner designed to simplify cleaning tasks by leveraging ultrasonic sensors, Arduino-based programming, and efficient motorized components.

Project Overview
This project presents a robotic vacuum cleaner capable of autonomously sweeping and mopping. It utilizes ultrasonic sensors to navigate and detect obstacles, ensuring effective and hands-free cleaning in various environments such as homes, malls, hospitals, and railway stations.

Features
Autonomous navigation with obstacle detection
Dual functionalities: sweeping and mopping
Compact design for cleaning tight spaces
Easy-to-use interface with scheduled cleaning options
Low maintenance and long-lasting operation
Components
Arduino Uno R3: Open-source microcontroller for hardware control
Ultrasonic Sensor: Obstacle detection and distance measurement
Micro Servo Motor: Precise angular movement
Buzzer: Audible alerts for obstacle detection
DC Motor: Vacuum suction mechanism
Gear Motors: Movement control
H-Bridge Motor Driver: Power management for motors
RGB-LED Indicator: Status indication
Slide Switch: Manual power control
Power Supply: Batteries for mobility
Circuit and Working
Circuit Connections:
Components like the ultrasonic sensor, motors, and LEDs are connected to the Arduino board via an H-Bridge driver. A slide switch is used to control the power supply to the vacuum motor and mop.

Working Principle:

The ultrasonic sensor acts as the robot's eyes, transmitting and receiving signals to measure distances.
The Arduino processes these inputs and directs the motors accordingly to avoid obstacles.
Simultaneously, the vacuum motor provides suction to collect dust, and the mop motor assists in cleaning.
Code Functionality:
The Arduino program enables the robot to navigate, stop for obstacles, and clean surfaces efficiently.

Results
Without Obstacle: Indicator LED and buzzer remain off, allowing the robot to move freely.
With Obstacle: Indicator LED and buzzer activate, and the robot changes direction to avoid collision.
Advantages
Hands-free operation and compact design
Saves time and energy with efficient cleaning
Accesses hard-to-reach areas
Supports scheduled cleaning
Limitations
Cost-intensive initial setup
Risk of getting stuck or flipped over
Limited battery life and dustbin capacity
Ineffectiveness on stairs and thick carpets
Future Developments
Integration with security cameras for dual functionality
Metal scanners to avoid picking up valuable items
Edge-detection features for cleaning surfaces like tables
Tools and Platform
Platform: Tinkercad
Programming: Arduino IDE
