<div align="center">

# 🕷️ Quadruped Spider Robot

### STM32-Based Four-Legged Robotic Platform with 3D-Printed Mechanical Design, Servo Motion Control, and Vision-Based Obstacle Detection

![Quadruped Spider Robot](Our_Robot.jpg)

</div>

---

## 📌 Overview

**Quadruped Spider Robot** is an embedded robotics project focused on the design, manufacturing, assembly, and control of a four-legged spider-style robot. The project combines mechanical design, 3D-printed parts, STM32-based embedded control, servo-driven locomotion, and camera-based image processing for obstacle detection and destination reaching.

The robot was first modeled mechanically, then its parts were manufactured using 3D printing and assembled into a functional robotic platform. After the hardware implementation, the movement patterns were programmed and a vision-based navigation layer was added using image processing techniques.

---

## ✨ Key Features

- 🦿 **Four-legged spider robot structure** with servo-actuated movement
- 🧠 **STM32F103C8T6 microcontroller** as the main embedded controller
- 🖨️ **3D-printed mechanical components** designed and manufactured for the robot body
- 🎮 **Servo motor control** for robotic leg movement
- 📷 **ESP32-CAM module** for visual input
- 🚧 **Obstacle detection** using image processing
- 🎯 **Destination-reaching behavior** using existing navigation algorithms
- 🧩 Includes mechanical design files, embedded code, and thesis documentation

---

## 🧠 Project Idea

The main goal of this project was to build a complete quadruped robot from mechanical design to embedded implementation. The workflow included:

1. Designing the robot body and mechanical structure
2. Manufacturing the parts using 3D printing
3. Assembling the robot hardware
4. Programming movement patterns for the legs
5. Adding camera-based image processing
6. Detecting obstacles and navigating toward a target destination

---

## 🛠️ Hardware Components

| Component | Description |
|---|---|
| **STM32F103C8T6** | Main processor based on ARM Cortex-M3 |
| **SG90 Servo Motors** | Actuators used for leg movement |
| **ESP32-CAM** | Camera module for image processing and visual feedback |
| **HJS-480-0-24 Power Supply** | Source voltage supply for the robot system |
| **3D-Printed Parts** | Mechanical body and leg structure |

---

## 💻 Software & Tools

| Tool / Technology | Purpose |
|---|---|
| **STM32CubeMX** | Microcontroller configuration and initialization |
| **Keil MDK-ARM** | Embedded C development and firmware programming |
| **C / Embedded C** | Robot control firmware |
| **SolidWorks** | Mechanical design and 3D modeling |
| **Image Processing** | Obstacle detection and navigation support |
| **LaTeX** | Thesis documentation |

---

## 🦿 Locomotion Concept

The robot uses multiple SG90 servo motors to generate walking motion. Each leg movement is controlled through embedded firmware running on the STM32F103C8T6 microcontroller. By coordinating the servo angles, the robot can perform step-based movement similar to a spider-like quadruped mechanism.

---

## 📷 Vision & Navigation

The ESP32-CAM module provides visual input for the robot. Image processing is used to detect obstacles in the environment, allowing the robot to make navigation decisions and move toward the destination using implemented algorithms.

---

## 🧪 Results

The project includes several stages of mechanical and system development:

- Robot body without motors
- Front-view assembled robot
- Top-view assembled robot
- Final SolidWorks design version
- Final physical robot prototype

You can find the mechanical design files in the `Solid/` folder and the thesis documentation in the `Thesis/` folder.

---

## 📚 Documentation

This repository contains both implementation files and academic documentation:

- Embedded STM32 project files
- CubeMX configuration
- Mechanical CAD files
- Thesis PDF
- Thesis LaTeX source files
- Robot images and design results

---

## 👥 Authors

**Mohammad Barabadi**  
GitHub: [@mohammadbrd](https://github.com/mohammadbrd)

**Sajad Ghadiri**  
GitHub: [@Sajad-Ghadiri](https://github.com/Sajad-Ghadiri)

---

## 📄 License

No license file is currently included in this repository.  
If you plan to reuse, modify, or distribute this project, please contact the authors first.

---

<div align="center">

### ⭐ If you find this project useful, consider starring the repository.

</div>
