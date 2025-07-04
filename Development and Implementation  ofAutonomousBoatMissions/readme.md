
https://github.com/user-attachments/assets/0ce049ec-dcd6-484d-9ad8-cc37d7dbc26a
# ROS Development for Autonomous Boat Navigation System

## Overview

This directory contains the ROS (Robot Operating System) development components for the Autonomous Boat Navigation System, developed as part of an end-of-studies project. The ROS implementation integrates the asv_wave_sim package for simulation, incorporates the mechanical design of the autonomous boat, and includes an autonomous navigation program using the Gmapping algorithm for mapping and waste-cleaning operations in aquatic environments.

## Purpose

The ROS development aims to:





Simulate the autonomous boat in various aquatic conditions using the asv_wave_sim package.



Integrate the mechanical design with ROS for real-time control and navigation.



Enable autonomous mapping of the environment using the Gmapping SLAM algorithm.



Develop an autonomous navigation program for detecting and collecting waste in water bodies.

## Design Details





Simulation with asv_wave_sim: The asv_wave_sim package is used to simulate the boat’s dynamics in water, accounting for wave interactions and environmental conditions. The mechanical design is incorporated into the simulation for accurate testing.



Mechanical Integration: The boat’s mechanical components (propulsion system, sensor mounts) are interfaced with ROS1 Noetic via custom nodes.



Gmapping Implementation: The Gmapping SLAM algorithm processes sensor data to generate 2D occupancy grid maps of the environment, enabling the boat to localize itself and navigate autonomously.





Autonomous Waste Cleaning: The navigation program uses the generated maps to plan paths, detect waste , and execute cleaning operations. The program controls the actuators to approach and collect waste.

## Video of obstacle avoidance
This video explain the avoidance obstacle strategie






