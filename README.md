# Autonomous-water-turret-IOT
Autonomous Water Turret IoT is a smart system designed to detect and extinguish fires using artificial intelligence and IoT technology. It uses a camera and a YOLOv5 deep learning model to identify fire in real time, then automatically aims a water jet at the fire with servo motors and activates a water pump. 

## Overview

**Autonomous Water Turret IoT** is a smart fire detection and suppression system using Internet of Things (IoT) and Artificial Intelligence (AI). It detects fire using a YOLOv5 deep learning model via a webcam and precisely aims a water jet using servo motors, controlled via Arduino.

## Features

- Real-time fire detection (YOLOv5s)
- Auto-targeting via servo motors
- Water pump activation on detection
- Precise suppression to minimize water waste
- Fully autonomous operation

## Hardware

- Arduino Uno
- 5V Submersible Water Pump
- Relay Module
- Servo Motors SG90 (Pan & Tilt)
- Webcam (for live feed)
- Breadboard, Jumper Wires
- 5V Power Adapter

## Software & ML Model

- YOLOv5s Object Detection (PyTorch/Ultralytics)
- Python for detection and control logic
- Serial communication with Arduino

## Logic Flow

1. Webcam captures live feed.
2. YOLOv5s model detects fire regions.
3. Calculates offset from frame center.
4. Servo motors aim nozzle at fire.
5. Water pump activates if aligned.
<img width="525" height="700" alt="image" src="https://github.com/user-attachments/assets/d4cc1e7b-c815-463b-aeb0-28324c670a7f" />

## Circuit Diagram

<img width="725" height="371" alt="image" src="https://github.com/user-attachments/assets/8bc6c606-f4ac-4132-9d5d-5236a9353481" />


## Results

- Accurate detection with confidence scores above 0.7
- Fast servo alignment
- Minimal water usage
- Responsive, real-time operation
-
- <img width="765" height="702" alt="image" src="https://github.com/user-attachments/assets/28e3bea5-eaa2-401c-8b05-f8c81494a687" />

<img width="660" height="558" alt="image" src="https://github.com/user-attachments/assets/6ff4e734-ef4e-4a7b-9ee9-001097b80929" />

<img width="846" height="344" alt="image" src="https://github.com/user-attachments/assets/8d01c568-1996-40ba-a3f4-e4e7b678a62d" />



## Challenges

- Serial communication delay
- Servo motor jitter
- YOLOv5 tuning for false positives
- Power supply separation for pump

## Future Scope

- Fire size estimation (dynamic water control)
- Remote monitoring via IoT dashboards
- Multi-axis coverage
- Integration of smoke/gas sensors
- Battery backup for emergency


## License

Include license info if any.

