<div align="center">

# 🕷️ HexaBot
### AI Assisted Smart Hexapod Robot for Rough Terrain Navigation

<img src="images/robot.png" width="700">

[![Status](https://img.shields.io/badge/Status-Under%20Development-blue)]
[![Platform](https://img.shields.io/badge/Platform-ESP8266-success)]
[![Servos](https://img.shields.io/badge/18-High%20Torque%20Servos-red)]
[![Track](https://img.shields.io/badge/SCAI%202026-Track%201-blueviolet)]
[![License](https://img.shields.io/badge/License-MIT-green)]

---

### 🚀 SCAI 2026 Project
### Track T1 — Smart Sensing & Intelligent Electronic Systems

Building a biologically inspired six-legged walking robot capable of stable locomotion over rough terrain using inverse kinematics, intelligent gait generation, and embedded control.

</div>

---

# 📖 Overview

Traditional wheeled robots perform well on flat surfaces but struggle in uneven environments such as rocky terrain, agricultural fields, forests, and disaster zones.

HexaBot is designed to overcome these limitations using six independently actuated legs capable of maintaining stability while walking over irregular terrain.

The robot combines

- Embedded Systems
- Smart Sensing
- Motion Control
- Inverse Kinematics
- Servo Synchronization

to create a stable and intelligent walking platform.

---

# 🎯 Project Objectives

✔ Stable six-legged locomotion

✔ High torque actuation

✔ Modular electronics architecture

✔ Wireless control using ESP8266

✔ Expandable sensor platform

✔ Future autonomous navigation

---

# ✨ Features

- 18 Degrees of Freedom
- 6-Leg Walking Mechanism
- Tripod Gait
- Inverse Kinematics
- Smooth Servo Interpolation
- Modular Electronics
- WiFi Control
- Real-Time Servo Calibration
- Easily Expandable
- Battery Powered (Future)

---

# ⚙ Hardware

| Component | Specification |
|------------|--------------|
| Controller | ESP8266 |
| Servo Driver | PCA9685 |
| Servo Motors | 18 × RKI1203 35kg·cm |
| Number of Legs | 6 |
| Servo per Leg | 3 |
| Total Servos | 18 |
| Power Supply (Current) | 8.4V SMPS |
| Future Power Source | 2S Li-ion Battery |
| CAD Software | Fusion 360 |

---

# 🦿 Mechanical Design

Each leg contains three joints.

```
Body
 │
 ├── Coxa
 │
 ├── Femur
 │
 └── Tibia
```

Each leg provides

- Hip Rotation
- Lift Motion
- Extension Motion

Total

```
6 Legs × 3 DOF = 18 DOF
```

---

# 🔌 Electronics Architecture

```
                 +------------------+
                 |    ESP8266       |
                 +--------+---------+
                          |
                     I2C Bus
                          |
                 +--------+---------+
                 |     PCA9685      |
                 +--------+---------+
                          |
               -----------------------
              | 18 PWM Servo Outputs |
               -----------------------
                          |
                 RKI1203 Servo Motors

Power

AC Supply
     │
SMPS 8.4V
     │
Power Distribution
     │
Servo Driver
     │
Servos
```

Future Version

```
2S Li-ion Battery

↓

Fuse

↓

Buck Converter

↓

ESP8266

↓

PCA9685

↓

Servo Motors
```

---

# 🧠 Software Architecture

```
Initialization

↓

Servo Calibration

↓

Stand Position

↓

Gait Generation

↓

Inverse Kinematics

↓

Servo Angle Calculation

↓

PWM Generation

↓

Walking Motion
```

---

# 🚶 Planned Gaits

- Stand
- Sit
- Tripod Gait
- Ripple Gait
- Wave Gait
- Rotate Left
- Rotate Right
- Crab Walk

---

# 📂 Repository Structure

```
HexaBot/

│
├── README.md
├── LICENSE
│
├── firmware/
│      ├── esp8266/
│      ├── stm32/
│      └── pca9685/
│
├── cad/
│      ├── Fusion360/
│      ├── STL/
│      └── Drawings/
│
├── docs/
│      ├── Mechanical.md
│      ├── Electronics.md
│      ├── Kinematics.md
│      └── Gait.md
│
├── hardware/
│      ├── Wiring
│      └── Schematics
│
├── images/
│
├── videos/
│
└── report/
```

---

# 🚧 Development Status

| Module | Status |
|---------|--------|
| Mechanical Design | ✅ |
| CAD | ✅ |
| Chassis Assembly | ✅ |
| Servo Installation | ✅ |
| ESP8266 Firmware | 🟡 |
| PCA9685 Integration | 🟡 |
| Servo Calibration | 🟡 |
| Walking Algorithm | 🟡 |
| Wireless Control | 🔜 |
| Battery Operation | 🔜 |
| Obstacle Detection | 🔜 |

---

# 🔬 Future Improvements

- IMU Stabilization
- Ultrasonic Obstacle Detection
- Computer Vision
- SLAM
- ROS2 Integration
- Autonomous Navigation
- Terrain Classification
- AI Based Gait Selection

---

# 📷 Project Gallery

(Add photos here)

```
images/

robot_front.jpg

robot_side.jpg

servo_mount.jpg

cad_design.png

walking.gif
```

---

# 🎥 Demonstration

(Add YouTube video or GIF)

```
videos/demo.mp4
```

---

# 🏆 SCAI 2026

This repository is developed as a project submission for

**SCAI 2026**

**Track T1**
### Smart Sensing & Intelligent Electronic Systems

The objective is to develop a working intelligent robotic platform demonstrating embedded control, smart sensing capability, and robust locomotion over uneven terrain.

---

# 👨‍💻 Team

Team Name

(To be Updated)

Members

- Your Name

Mentor

- (Faculty Guide)

---

# ⭐ Support

If you found this project interesting,

⭐ Star the repository.

Feedback and suggestions are always welcome.
