# Hardware Integration and Testing for Autonomous Boat Navigation System
## Overview
This directory details the hardware integration and testing for the Ocean Cleaner, an autonomous boat designed for waste collection. It covers the setup of the Raspberry Pi environment, integration of critical components (LIDAR, IMU, GPS, camera, motors), and power system configuration, ensuring reliable communication, navigation, and operation in aquatic environments.
## Purpose

Integrate hardware components with ROS Noetic for autonomous navigation and waste collection.
Validate system performance through unit, integration, and system-level testing in simulated and real-world conditions.
Ensure reliable power distribution and protection against water exposure.

## Components

Raspberry Pi 4: Central processing unit running Ubuntu 20.04 and ROS Noetic.
RPLIDAR A1: Provides real-time laser scanning for mapping and obstacle avoidance.
9-axis IMU: Supplies orientation and acceleration data via I2C.
SIM808 GPS: Enables geolocation via UART through an Arduino Uno intermediary.
Camera Module: Supports vision-based perception via CSI port.
Motor Control System: Uses Arduino Uno and ESCs for differential steering of APISQUEEN U2 MINI thrusters.
Power System: Combines a TECTIN 20000mAh power bank and Zeee 4S 14.8V 5200mAh LiPo batteries.
## Wiring Raspberry PI 4 and IMU
![mpu_](https://github.com/user-attachments/assets/9b61175d-a30a-43ea-8f60-ff42647a2735)
## Wiring Raspberry PI 4 + Arduino + GPS Module SIM808
![gps_ard_pi](https://github.com/user-attachments/assets/4a998ac0-f828-46fe-ac69-69627a5d10ba)

##  Motor Control System Wiring Diagram

![motor_system](https://github.com/user-attachments/assets/1c281fcd-0e9a-4af2-b8e1-b99bb065181b)
