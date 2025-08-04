# ROS2 Humble – Turtlesim Task

This document describes the tasks performed using ROS2 Humble and the Turtlesim package. It summarizes the steps carried out to complete the assignment.

---

## Table of Contents
- [Overview](#overview)
- [1. Environment Setup](#1-environment-setup)
- [2. ROS2 and Turtlesim Installation](#2-ros2-and-turtlesim-installation)
- [3. Task Steps](#3-task-steps)
- [4. Summary](#4-summary)

---

## Overview
The objective of this task was to set up a virtualized Ubuntu environment, install ROS2 Humble, and use the Turtlesim package to perform basic operations such as running the simulator, moving turtles, spawning additional turtles, changing the background color, and controlling multiple turtles.

---

## 1. Environment Setup
- Installed **VirtualBox** on the host machine.
- Created a new Virtual Machine with:
  - Ubuntu 22.04 (64-bit)
  - 4 GB RAM
  - 20 GB Storage
- Installed Ubuntu successfully inside the virtual environment.

---

## 2. ROS2 and Turtlesim Installation
- Installed ROS2 Humble Desktop version and verified with `ros2 --version`.
- Installed the Turtlesim package for ROS2.

---

## 3. Task Steps
### Step 1: Launch Turtlesim
- Started the Turtlesim node to open a simulation window with a turtle.

### Step 2: Move the Turtle
- Used the keyboard teleoperation node to manually move the turtle around the simulation window.

### Step 3: Spawn a Second Turtle
- Used a ROS2 service call to create another turtle in a different position.

### Step 4: Change Background Color
- Modified Turtlesim background parameters and applied them to visually change the simulation background color.

### Step 5: Control Multiple Turtles
- Configured command remapping to control the second turtle independently from the first turtle.

---

## 4. Summary
This task demonstrated the following:
- Setting up ROS2 and using nodes, topics, services, and parameters.
- Successfully interacting with the Turtlesim simulation.
- Performing operations such as spawning multiple turtles, changing the environment, and independently controlling multiple turtles.



