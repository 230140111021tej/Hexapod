<div align="center">

# 🕷️ HexaBot
### AI Assisted Smart Hexapod Robot for Rough Terrain Navigation

<img src="images/hexapod.png" width="850">

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

<p align="center">
<img src="images/top_layout.png" width="850">
</p>

<p align="center">
<b>Complete CAD layout showing the chassis, servo placement and complete leg assembly.</b>
</p>

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

## Robot Specifications

| Parameter | Value |
|-----------|------|
| Weight (Without Battery) | **3.1 kg** |
| Weight (With Battery) | **3.4 kg** |
| Number of Legs | 6 |
| Degrees of Freedom | 18 |
| Servo Motors | 18 × RKI1203 |
| Servo Torque | 35 kg·cm |
| Controller | ESP8266 |
| PWM Driver | PCA9685 |
| CAD Software | Fusion 360 |

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

## Hardware Components

<p align="center">

<img src="images/ESP8266-Pinout-NodeMCU.png" width="220">

<img src="images/PCA9685-Module-Pinout.png" width="320">

<img src="images/RKI1203_Servo.jpg" width="220">

</p>

<p align="center">
<b>ESP8266 NodeMCU, PCA9685 PWM Driver and RKI1203 35kg·cm High Torque Servo.</b>
</p>

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

## Leg Design

<p align="center">

<img src="images/coxa.png" width="250">

<img src="images/femur.png" width="250">

<img src="images/tibia.png" width="250">

</p>

<p align="center">
<b>Custom designed Coxa, Femur and Tibia links developed in Fusion 360.</b>
</p>

---

## Central Chassis

<p align="center">
<img src="images/trunk_body.png" width="450">
</p>

<p align="center">
<b>Lightweight optimized central body supporting six independent robotic legs.</b>
</p>

---

## Servo Mount

<p align="center">
<img src="images/servo_mount.png" width="500">
</p>

<p align="center">
<b>Custom designed high-strength servo mounting bracket.</b>
</p>

---

## Shock Absorbing Foot

<p align="center">
<img src="images/foot.png" width="250">
</p>

<p align="center">
<b>Spring assisted foot mechanism for better terrain adaptability.</b>
</p>

---
