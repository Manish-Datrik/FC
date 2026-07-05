# Travel Navigation Controller PCB

## About the Project

This project is a travel controller PCB that I designed using EasyEDA. The main goal of this project was to learn how to design a complete PCB from the beginning, starting with the schematic and ending with a ready-to-manufacture board.

The board is built around the ESP32 microcontroller and can be used as the control system for a small drone or robotic vehicle. It supports multiple sensors, RC receiver input, and motor controllers, making it useful for outdoor and travel-related applications.

---

## Travel Purpose

This project is designed for travel and outdoor activities.

It can be used in situations like:

- Trekking
- Camping
- Mountain trips
- Forest exploration
- Adventure travel
- Outdoor photography
- Remote area navigation

The controller can be used inside a drone or rover that helps travelers explore places safely. It can capture aerial views, monitor difficult paths, inspect areas before walking, or simply help record beautiful travel memories from different angles.

Since the board uses an ESP32, more features like GPS, wireless communication, or sensors can also be added in the future.

---

## What I Used

- EasyEDA
- ESP32 DevKit V1
- MPU6050 Motion Sensor
- RC Receiver Connector
- ESC Connectors
- I2C Expansion Headers
- Resistors
- Diode
- Power Connectors

---

## What I Did

### 1. Started the Project

I created a new project in EasyEDA and opened a new schematic.

---

### 2. Added Components

I searched for all the required components and placed them one by one.

Main components include:

- ESP32 DevKit
- MPU6050
- RC Receiver Header
- ESC Connectors
- I2C Headers
- Power Connectors
- Resistor
- Diode

---

### 3. Created the Schematic

After placing all the components, I connected them using wires and net labels.

The schematic includes:

- ESP32 as the main controller
- MPU6050 connected through I2C
- RC receiver input
- Multiple ESC outputs for motors
- I2C expansion ports for additional sensors
- Power and ground connections
---

### 4. Converted to PCB

After finishing the schematic, I converted it into PCB layout.

All the components were transferred automatically.

---

### 5. Component Placement

I arranged the components neatly to make routing easier and keep the board compact.

---

### 6. PCB Routing

I routed all the tracks carefully.

Power and signal lines were connected properly while keeping the layout clean.

---

### 7. Final Checking

After routing, I checked the PCB for connection errors and made sure every component was connected correctly.

---

### 8. Manufacturing Files

Finally, I generated the Gerber and drill files that can be used for PCB manufacturing.

---

## Features

- ESP32 based controller
- MPU6050 motion sensor
- RC receiver support
- Multiple ESC outputs
- I2C expansion ports
- Compact PCB design
- Easy to upgrade
- Suitable for outdoor projects

---

## What I Learned

While working on this project, I learned:

- How to use EasyEDA
- How to create a schematic
- How to connect electronic components
- How to design a PCB
- How to place components properly
- How to route PCB tracks
- How to check design errors
- How to generate Gerber files

---

## Project Files

```text
Travel-Navigation-Controller
│
├── Schematic
├── PCB Layout
├── Gerber Files
├── Images
└── README.md
```

**Manish Vanjari**
GitHub: https://github.com/Manish-Datrik/FC.git
