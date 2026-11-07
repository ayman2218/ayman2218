# Ayman Adriouech

**Robotics, Automotive and Embedded AI Engineering Student**

Autonomous systems · ADAS · ROS2 · Embedded deep learning · ISO 26262

[Portfolio](https://ayman-adriouech.github.io) · [LinkedIn](https://www.linkedin.com/in/ayman-adriouech-9b80b6277) · [Email](mailto:ayman.adriouech@ueuromed.eidia.org)

---

## About

Engineering student focused on robotics, embedded systems and applied artificial intelligence. My work covers computer vision, embedded AI, ROS2, sensor integration and automotive electrical architecture. I am looking for a **technical internship** in robotics, automotive or embedded systems.

- **Focus:** autonomous navigation, ADAS, embedded AI and real-time control
- **Studies:** Robotics and Automotive Engineering, Euro-Mediterranean University of Fez (UEMF-EIDIA), 2024 – 2026
- **Research:** deep learning compression for automotive ECUs (PQK pipeline)
- **Leadership:** President of Digi Club
- **Goal:** deploy intelligent perception systems on real automotive embedded platforms

---

## Experience

### PFA Intern, Zonal Architecture Engineering
**LEONI** · SMART CAR project, electric Citroën C3 · 2025 – 2026

- Designed an AI-assisted zonal electrical architecture, following the DMAIC approach.
- Reworked the harness topology (13 HX2ML variants into 9 families) with Capital Harness.
- Integrated ADAS functions and sized 6 zonal control units (ZCU).
- Analysed in-vehicle networks (LIN, CAN FD, Automotive Ethernet) and functional safety (ISO 26262, HARA, ASIL).

### Mobile Robotics Intern
**CleanFlex** · 2 months · 2025

- Built an autonomous cleaning robot on TurtleBot3 with ROS2 and SLAM.
- Developed autonomous navigation and integrated a LiDAR, an IMU and an RGB-D camera.

---

## Research

### PQK Pipeline: deep learning compression for automotive ECUs (2025)

*Compression de Modèles de Deep Learning pour ECU Automobile : Pipeline Intégré de Pruning, Quantization et Knowledge Distillation*

An integrated pipeline of structured pruning, post-training quantization and knowledge distillation, built to deploy deep learning models on resource-constrained automotive ECUs. Validated on the GTSRB dataset (43 traffic sign classes).

| Metric | Original | PQK compressed | Change |
|---|---|---|---|
| Inference latency (mean) | 45.2 ms | 8.3 ms | −81.6 % |
| Worst-case execution time | 52.1 ms | 10.1 ms | −80.6 % |
| Model size | 65.0 MB | 12.0 MB | −81.5 % (5.4×) |
| Accuracy | 94.2 % | 92.5 % | −1.7 pts |
| Jitter | 2.34 ms | 0.85 ms | −63.7 % |
| Deadline compliance (50 ms) | 98.5 % | 100 % | +1.5 pts |
| ISO 26262 level | n/a | ASIL B | compliant |

```
Original model (65 MB, 45.2 ms)
  → Structured pruning        −30 % parameters, −23 % latency
  → Post-training quantization  FP32 to INT8, −75 % size, −71 % latency
  → Knowledge distillation      +3.3 pts accuracy recovered
  → PQK model (12 MB, 8.3 ms, 92.5 %, ASIL B)
```

Keywords: model compression, ADAS, ECU, ISO 26262, real-time systems, YOLOv5, GTSRB

---

## Projects

| Year | Project | Stack | Summary |
|---|---|---|---|
| 2025 | **Fuzzy logic for ADAS functions** | Raspberry Pi 5, fuzzy logic, HIL | Embedded controller for autonomous parking and line following, validated with hardware-in-the-loop. |
| 2025 | **Autonomous robotic chair** | ROS2, Nav2, SLAM, LiDAR | Autonomous navigation, trajectory planning and 2D mapping, with odometry and IMU fusion. |
| 2025 | **Fall detection robot** | OpenCV, MediaPipe, PoseNet | Mobile robot with a computer vision pipeline for kinematic analysis of human posture. |
| 2025 | **Autonomous cleaning robot** | TurtleBot3, ROS2, SLAM | Internship project at CleanFlex, with LiDAR, IMU and RGB-D perception. |
| 2025 | **PQK compression pipeline** | Python, TensorFlow, YOLOv5, ONNX Runtime | Pruning, INT8 quantization and distillation for automotive ECUs, ASIL B under ISO 26262 analysis. |
| 2024 | **Embedded ADAS system** | Raspberry Pi, OpenCV, TensorFlow, CNN | Traffic sign detection, lane departure warning and real-time motor control driven by a CNN. |
| 2024 | **Chess-playing robot arm** | Computer vision, inverse kinematics, Raspberry Pi | Board recognition by vision and piece manipulation through inverse kinematics. |

---

## Skills

| Area | Tools and technologies |
|---|---|
| Programming | C, C++, Python, VHDL, Java (Android) |
| Robotics and embedded | ROS2, Nav2, SLAM, RTOS, Raspberry Pi, ESP32-S3, FPGA, PIC16F |
| Vision and AI | OpenCV, TensorFlow, CNN, YOLOv5, ONNX, machine learning, image processing |
| Automotive | ADAS, ISO 26262, HARA, ASIL, LIN, CAN FD, Automotive Ethernet, Capital Harness, DMAIC |
| Engineering and simulation | MATLAB, Simulink, Catia V6, Proteus, Quartus |
| Tools | Git, Linux |

---

## Education

| Period | Degree | Institution |
|---|---|---|
| 2024 – 2026 | Engineering in Robotics and Automotive | Euro-Mediterranean University of Fez (UEMF-EIDIA) |
| 2022 – 2024 | Integrated Preparatory Cycle | Euro-Mediterranean University of Fez (UEMF-EIDIA) |
| 2021 – 2022 | Baccalauréat, Experimental Sciences | Lycée Sidi Bennour |

## Certifications

- State Estimation and Localization for Self-Driving Cars, University of Toronto (Coursera)
- Visual Perception for Self-Driving Cars, University of Toronto (Coursera)
- ISO 26262, functional safety for automotive systems
- QHSE, quality, health, safety and environment
- Scrum Master

## Languages

Arabic (native) · French (C1) · English (B2) · Spanish (A2)

---

## Contact

Open to internships in robotics, automotive engineering and embedded AI.

[Portfolio](https://ayman-adriouech.github.io) · [LinkedIn](https://www.linkedin.com/in/ayman-adriouech-9b80b6277) · [ayman.adriouech@ueuromed.eidia.org](mailto:ayman.adriouech@ueuromed.eidia.org)
