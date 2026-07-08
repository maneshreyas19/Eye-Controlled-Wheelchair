# Smart Eye Controlled Wheelchair

An intelligent assistive wheelchair that enables hands-free navigation using eye movement detection through a laptop camera. The system combines computer vision, embedded control, and obstacle detection to provide safe and accessible indoor mobility for individuals with limited physical movement.

---

## Project Overview

This project aims to improve the independence and mobility of users with physical disabilities by replacing conventional joystick-based control with eye movement detection. A laptop camera captures facial movements and tracks eye direction to generate movement commands for an Arduino Nano-controlled wheelchair.

The wheelchair also integrates ultrasonic sensors for obstacle detection, ensuring safe navigation in indoor environments.

---

## Objectives

- Develop a hands-free wheelchair control system
- Detect eye movements using computer vision
- Control wheelchair direction using Arduino Nano
- Implement automatic obstacle detection
- Improve user accessibility and independence
- Enhance indoor navigation safety

---

## Key Features

- Eye-controlled navigation
- Laptop camera-based face tracking
- Hands-free wheelchair operation
- Real-time movement control
- Ultrasonic obstacle detection
- Automatic motor stopping
- Indoor navigation support
- Low-cost embedded implementation

---

## Hardware Components

- Arduino Nano
- Motor Driver Module
- DC Motors
- Ultrasonic Sensor
- Laptop Camera
- Metal Chassis
- Rechargeable Battery
- Wheels and Gear Motors

---

## Software

- Arduino IDE
- Embedded C++
- Computer Vision (Face/Eye Tracking)
- Serial Communication

---

## Working Principle

1. Laptop camera captures the user's face.
2. Face tracking software detects eye direction.
3. Eye movements are translated into movement commands.
4. Commands are transmitted to the Arduino Nano.
5. Arduino controls the motor driver.
6. DC motors move the wheelchair accordingly.
7. Ultrasonic sensors continuously detect nearby obstacles.
8. The wheelchair automatically stops or avoids collisions when an obstacle is detected.

---

## System Architecture

```
Laptop Camera
      │
      ▼
Face & Eye Tracking
      │
Movement Commands
      │
      ▼
Arduino Nano
      │
 ┌────┴────┐
 │         │
 ▼         ▼
Motor   Ultrasonic
Driver   Sensors
 │
 ▼
DC Motors
 │
 ▼
Wheelchair Movement
```

---

## Performance

- Obstacle Detection Accuracy: 78%
- Hands-Free Navigation
- Real-Time Direction Control
- Indoor Obstacle Detection
- Improved User Accessibility

---

## Applications

- Assistive Mobility
- Smart Healthcare
- Hospitals
- Rehabilitation Centers
- Elderly Care
- Home Automation
- Research in Human–Computer Interaction

---

## Advantages

- Hands-free operation
- Improved accessibility
- Low-cost solution
- Safe indoor navigation
- Easy to operate
- Modular hardware design
- Expandable architecture

---

## Repository Structure

```
Eye-Controlled-Wheelchair
│
├── docs/
├── firmware/
├── computer-vision/
├── hardware/
├── circuit-diagrams/
├── images/
├── test-results/
├── README.md
└── LICENSE
```

---

## Current Status

**Documentation Available**

This repository currently includes the project documentation, architecture, hardware overview, and system design. Firmware, computer vision scripts, circuit schematics, and implementation files will be added in future updates.

---

## Future Improvements

- Upload Arduino firmware
- Add OpenCV-based eye tracking implementation
- Upload circuit schematics
- Integrate wireless communication
- Improve obstacle detection accuracy
- Add mobile application support
- Implement autonomous navigation
- Enable voice-assisted control

---

## Author

Shreyas Mane

B.Tech Electronics and Communication Engineering
