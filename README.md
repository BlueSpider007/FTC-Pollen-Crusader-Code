***
# 🤖 Pollen Crusader | FTC Robot Codebase

![Robot Status](https://img.shields.io/badge/Status-Active-success)
![Platform](https://img.shields.io/badge/Platform-FTC-blue)
![Language](https://img.shields.io/badge/Language-Java-orange)

**Pollen Crusader** is the official software repository for our FIRST Tech Challenge (FTC) robot. This codebase manages the motor control, sensor integration, vision processing, and autonomous routines required to compete in the BIOBUZZ season.

##  Project Overview
The Pollen Crusader is designed to complete the objectives of this seasons game before falling apart. 

### Key Features
*   **Feature 1 Mecanum Drive:** Smooth, omnidirectional movement with PID control. (If we can afford it)
*   **Feature 2 Vision System:** Uses AprilTags to identify and track game elements.
*   **Feature 3 Rotating Turret:** A high-speed cannon for rapid scoring.
*   **Feature 4 Auto Routine:** A multi-step autonomous pathing script. (Countless tokens will be spent on this)

## 🛠 Hardware Configuration
The robot is built on the following hardware stack:
*   **Controller:** REV Control Hub / Expansion Hub
*   **Motors:** REV HD Motors
*   **Drive System:** 4-wheel Mecanum, hopefully

## 💻 Software Stack
*   **Language:** Java
*   **SDK:** FTC Robot Controller SDK
*   **Libraries:** [e.g., OpenCV, AprilTag, PIDController]
*   **Build System:** Gradle

## 📂 Project Structure
```text
├── src/main/java/org/team[Number]/robot/
│   ├── TeleOp/          # Teleoperated driver control logic
│   ├── Autonomous/      # Autonomous pathing and routines
│   ├── Hardware/        # Motor and Sensor hardware definitions
│   ├── Vision/          # OpenCV and AprilTag processing
│   ├── Utils/           # Helper classes (PID, Math, etc.)
│   └── RobotConfig.java # Global constants and configuration
├── assets/              # Robot images and assets
└── build.gradle         # Gradle build configuration
```

## ⚙️ Getting Started

### Prerequisites
1.  **Android Studio** (Latest stable version)
2.  **FTC Robot Controller** (Connected via WiFi or USB)
3.  **Java JDK** 11 or higher

---
*Made by a random AI for the FIRST Tech Challenge.*
