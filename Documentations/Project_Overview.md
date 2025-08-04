# 📦 Project Overview: Automated Packaging Inspection System

## 🧠 Project Title

**Automated Packaging Inspection System with HMI Monitoring and Factory I/O Simulation**

---

## 🎯 Objective

This project aims to simulate an automated packaging inspection system using **Siemens PLC** and an **HMI monitoring system**. It replicates an industrial process that inspects packages on a conveyor belt, detects any defects, and diverts faulty packages. The system also provides real-time monitoring through an HMI interface.

---

## 📚 Project Scope

This system simulates an automated packaging inspection process where packages move along a conveyor and pass through multiple inspection points. At each point, packages are checked for:

- **Presence**
- **Labelling**
- **Weight conformity**

Packages that fail inspection are automatically rejected via an actuator. The system operation, including defect counters, can be monitored and controlled through an HMI.

The system is implemented in **Siemens TIA Portal** using ladder logic, with the **HMI developed in WinCC**, and the overall process is visually simulated in **Factory I/O**.

---

## 🚫 Project Limitations

- No physical hardware is used — this is a fully virtual simulation.
- Label and weight checks are based on assumptions or timing logic, not real sensors.
- No communication with external systems (e.g., SCADA, databases).
- No integration with advanced machine vision systems.

---

## 🧩 System Components

### 🔍 Sensors

1. **Photoelectric Sensor** – Detects presence of packages
2. **Weight Sensor** – Simulated weight check (based on object type/timer)
3. **Barcode Scanner** – Simulated label detection (object ID or timing logic)

### ⚙️ Actuators

1. **Conveyor Motor** – Moves packages along the line
2. **Stop Blade** – Halts package at weight inspection point
3. **Pusher Cylinder** – Rejects faulty packages
4. **Chute Conveyor** – Transports rejected packages

---

## 🖥️ HMI Features

1. **Reject and Pass Counters**
2. **Start, Stop, and Reset Controls**
3. **Real-Time Operation Status Monitoring**

---

## 🛠 PLC Software and Tools

- **Siemens TIA Portal** – PLC programming and HMI design
- **Factory I/O** – 3D simulation of industrial process

---

## 🎓 Learning Objectives

1. Learn PLC programming using Siemens S7-1200 or S7-1500
2. Simulate sensors and actuators using Factory I/O
3. Design and integrate an HMI using WinCC in TIA Portal
4. Apply industrial automation design principles using Lean analysis


