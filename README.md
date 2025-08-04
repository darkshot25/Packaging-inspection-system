# Packaging-inspection-system
# 🏭 Automated Packaging Inspection System with HMI Monitoring and Factory I/O Simulation

This project simulates an automated packaging inspection line using **Siemens TIA Portal**, **Factory I/O**, and **WinCC HMI**. It mimics real-world industrial systems that inspect packages for defects and reject faulty ones, while enabling live monitoring and control through an HMI.

## 🎯 Objective

To design, program, and simulate an automated system that:
- Moves packages along a conveyor
- Inspects for presence, labeling, and weight conformity
- Automatically rejects defective packages
- Displays real-time operation status and counters on an HMI

The system is developed in Siemens TIA Portal and visually simulated using Factory I/O. It is a purely virtual implementation, suitable for training, learning, and portfolio demonstration.

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Siemens TIA Portal** | PLC programming (S7-1200), HMI design |
| **Factory I/O** | 3D simulation of industrial automation |
| **PLCSIM** | PLC code simulation |
| **WinCC (in TIA Portal)** | HMI monitoring and control |
| **GitHub** | Project documentation and version control |

---

## 📦 System Overview

### 🧠 Features
- Photoelectric sensor to detect packages
- Barcode scanner (simulated) for label presence
- Weight check logic using a stop blade and timer
- Rejector cylinder to push faulty packages
- Conveyor motor control with start/stop/reset
- Pass and reject counters
- HMI dashboard with status indicators and controls

### 📈 System Flow
1. Package enters conveyor
2. Presence sensor triggers inspection sequence
3. Label and weight logic simulated
4. Rejector pushes faulty package to chute
5. HMI shows system status and updates counters

---

## 📂 Project Structure

```bash
Automated-Packaging-Inspection-System/
│
├── documentation/
│   ├── Project_Overview.pdf
│   ├── Requirements_Spec.md
│   ├── IO_Mapping.xlsx
│   └── Control_Philosophy.md
│
├── plc/
│   ├── TIA_Project_Backup.zip
│   ├── Ladder_Screenshots/
│
├── hmi/
│   ├── WinCC_HMI_Backup.zip
│   ├── HMI_Design_Screenshots/
│
├── factory_io/
│   ├── Scene.fio
│   └── Screenshot.png
│
├── media/
│   ├── demo_video.mp4
│   └── thumbnail.png
│
└── README.md
