<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,3,5,30&height=200&section=header&text=Ayman%20ADRIOUECH&fontSize=70&fontColor=fff&animation=fadeIn&fontAlignY=38&desc=Robotics%20%26%20Automotive%20Engineer&descSize=22&descAlignY=60" width="100%"/>

<div align="center">

## 🤖 Robotics · Automotive · Embedded AI

**Autonomous Systems | ADAS | ROS2 | Embedded Deep Learning | ISO 26262**

### 🌍 Morocco &nbsp;|&nbsp; 📧 [ayman.adriouech@ueuromed.eidia.org](mailto:ayman.adriouech@ueuromed.eidia.org) &nbsp;|&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/ayman-adriouech)

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=1000&color=0F6E56&center=true&vCenter=true&width=800&lines=Autonomous+Robots+%7C+SLAM+%7C+ROS2+%7C+Nav2;ADAS+%7C+ECU+Deployment+%7C+ISO+26262;Deep+Learning+Compression+%7C+PQK+Pipeline;Raspberry+Pi+%7C+ESP32+%7C+FPGA+%7C+LiDAR;Building+the+future+of+intelligent+mobility+%F0%9F%9A%97" alt="Typing Animation" />

</div>

---

## 🎯 About Me

> *Étudiant ingénieur passionné par la robotique, les systèmes embarqués et l'intelligence artificielle appliquée. Compétent en vision artificielle, IA embarquée, ROS2 et intégration de capteurs. Recherche d'un **stage technique** dans la robotique, l'automobile ou l'embarqué.*

- 🤖 **Focus:** Autonomous navigation, ADAS systems, embedded AI & real-time control
- 🔬 **Currently:** Studying Robotics & Automotive Engineering at UEMF-EIDIA (2024–2026)
- 📄 **Research:** Deep Learning compression for Automotive ECU — PQK Pipeline (Pruning + Quantization + Knowledge Distillation)
- 🏆 **Leadership:** President of Digi Club
- 🎯 **Goal:** Deploy intelligent perception systems on real automotive embedded platforms

---

## 🎓 Education

| Period | Degree | Institution |
|--------|--------|-------------|
| 2024 – 2026 | 🎓 Engineering in Robotics & Automotive | Euro-Mediterranean University of Fez (UEMF-EIDIA) |
| 2022 – 2024 | 🔬 Integrated Preparatory Cycle | Euro-Mediterranean University of Fez (UEMF-EIDIA) |
| 2021 – 2022 | 📚 Baccalauréat — Sciences Expérimentales | Lycée Sidi Bennour |

---

## 💼 Experience

### 🏭 Mobile Robotics Intern — *CleanFlex* &nbsp;`2 months · 2025`

> Autonomous Cleaning Robot using **TurtleBot3**, **ROS2**, and **SLAM**

- Designed and deployed an autonomous navigation system with full SLAM integration
- Integrated **LiDAR**, **IMU**, and **RGB-D camera** for real-time environment perception
- Implemented autonomous path planning and obstacle avoidance pipelines

---

## 📄 Research & Publications

### 📰 PQK Pipeline — Deep Learning Compression for Automotive ECU &nbsp;`2025`

> *"Compression de Modèles de Deep Learning pour ECU Automobile: Pipeline Intégré de Pruning, Quantization et Knowledge Distillation"*

A research paper proposing a novel integrated pipeline to compress deep learning models for deployment on resource-constrained automotive ECUs, validated on the **GTSRB** dataset (43 traffic sign classes).

**Key Results:**

| Metric | Original Model | PQK Compressed | Improvement |
|--------|---------------|----------------|-------------|
| Inference Latency (MRT) | 45.2 ms | **8.3 ms** | ↓ 81.6% |
| Worst-Case Execution Time | 52.1 ms | **10.1 ms** | ↓ 80.6% |
| Model Size | 65.0 MB | **12.0 MB** | ↓ 81.5% (5.4×) |
| Accuracy | 94.2% | **92.5%** | −1.7% only |
| Jitter (determinism) | 2.34 ms | **0.85 ms** | ↓ 63.7% |
| Deadline Compliance (50ms) | 98.5% | **100%** | ✅ Full |
| ISO 26262 ASIL Level | — | **ASIL B** | ✅ Compliant |

**Pipeline stages:**
```
Original Model (65MB, 45.2ms)
    └─► Structured Pruning (P)     → −30% params, −23% latency
        └─► Post-Training Quantization (Q)  → FP32→INT8, −75% size, −71% latency
            └─► Knowledge Distillation (K)  → +3.3% accuracy recovery
                └─► Final PQK Model (12MB, 8.3ms, 92.5% acc, ASIL B ✅)
```

**Tags:** `Deep Learning` `Model Compression` `ADAS` `ECU` `Pruning` `Quantization` `Knowledge Distillation` `ISO 26262` `Real-Time Systems` `GTSRB` `YOLOv5`

---

## 🚀 Projects

### 🧹 Autonomous Cleaning Robot — *CleanFlex Internship* &nbsp;`2025`
**TurtleBot3 · ROS2 · SLAM · LiDAR · IMU · RGB-D**

Full autonomous mobile robot for cleaning environments. Real-time SLAM-based navigation with sensor fusion (LiDAR + IMU + RGB-D). Deployed in production environment during internship.

---

### ♿ Autonomous Robotic Chair &nbsp;`2025`
**ROS2 · Nav2 · SLAM · LiDAR · Odometry-IMU Fusion**

Designed an assistive autonomous wheelchair with full ROS2/Nav2 stack. Features 2D mapping with LiDAR, trajectory planning, real-time obstacle avoidance, and odometry–IMU sensor fusion for robust localization.

---

### 🚗 Embedded ADAS System — Raspberry Pi &nbsp;`2024`
**OpenCV · TensorFlow · CNN · Raspberry Pi · Real-Time**

Embedded driver assistance system running on Raspberry Pi with CNN-based traffic sign detection, lane departure warning, obstacle detection, and AI-driven real-time motor control.

---

### ♟️ Chess-Playing Robot Arm &nbsp;`2024`
**AI · Computer Vision · Inverse Kinematics · Raspberry Pi**

Robotic arm that autonomously plays chess using vision-based board recognition and precise piece manipulation via inverse kinematics. Full perception-to-actuation pipeline on embedded hardware.

---

### 🧠 PQK Deep Learning Compression Pipeline &nbsp;`2025`
**Python · TensorFlow · YOLOv5 · ONNX Runtime · ARM Cortex-A53**

Research implementation of the PQK pipeline: structured pruning → INT8 quantization → knowledge distillation, achieving 5.4× model compression and 81.6% latency reduction on simulated automotive ECU. ASIL B compliant under ISO 26262 analysis.

---

## 🛠️ Tech Stack

<div align="center">

### 🤖 Robotics & Autonomous Systems
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Nav2](https://img.shields.io/badge/Nav2-0F6E56?style=for-the-badge&logoColor=white)
![SLAM](https://img.shields.io/badge/SLAM-185FA5?style=for-the-badge&logoColor=white)
![TurtleBot3](https://img.shields.io/badge/TurtleBot3-22314E?style=for-the-badge&logoColor=white)
![RTOS](https://img.shields.io/badge/RTOS-0F6E56?style=for-the-badge&logoColor=white)

### 🚗 Automotive & ADAS
![ADAS](https://img.shields.io/badge/ADAS-185FA5?style=for-the-badge&logoColor=white)
![ISO26262](https://img.shields.io/badge/ISO%2026262-0F6E56?style=for-the-badge&logoColor=white)
![ECU](https://img.shields.io/badge/Automotive%20ECU-22314E?style=for-the-badge&logoColor=white)
![ASIL](https://img.shields.io/badge/ASIL%20B-185FA5?style=for-the-badge&logoColor=white)

### 🧠 AI · Computer Vision · Embedded DL
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![CNN](https://img.shields.io/badge/CNN-185FA5?style=for-the-badge&logoColor=white)
![YOLOv5](https://img.shields.io/badge/YOLOv5-22314E?style=for-the-badge&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)

### 💻 Programming
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-0F6E56?style=for-the-badge&logo=c&logoColor=white)
![VHDL](https://img.shields.io/badge/VHDL-185FA5?style=for-the-badge&logoColor=white)
![Java](https://img.shields.io/badge/Java%20Android-ED8B00?style=for-the-badge&logo=android&logoColor=white)

### ⚡ Hardware & Embedded
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22D2A?style=for-the-badge&logo=raspberrypi&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32--S3-22314E?style=for-the-badge&logo=espressif&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA-0F6E56?style=for-the-badge&logoColor=white)
![LiDAR](https://img.shields.io/badge/LiDAR-185FA5?style=for-the-badge&logoColor=white)
![IMU](https://img.shields.io/badge/IMU-22314E?style=for-the-badge&logoColor=white)
![RGB-D](https://img.shields.io/badge/RGB--D%20Camera-0F6E56?style=for-the-badge&logoColor=white)

### 🛠️ Tools & Software
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white)
![Catia V6](https://img.shields.io/badge/Catia%20V6-005386?style=for-the-badge&logo=dassaultsystemes&logoColor=white)
![Simulink](https://img.shields.io/badge/Simulink-0076A8?style=for-the-badge&logoColor=white)
![Proteus](https://img.shields.io/badge/Proteus-0066FF?style=for-the-badge&logoColor=white)
![Quartus](https://img.shields.io/badge/Quartus-0071C5?style=for-the-badge&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 🏆 Certifications

| Badge | Certification | Domain |
|-------|--------------|--------|
| 🛡️ | **QHSE** — Quality, Health, Safety & Environment | Safety Management |
| 🚗 | **ISO 26262** — Functional Safety for Automotive E/E Systems | Automotive Safety |
| ♻️ | **Scrum Master** | Agile Project Management |
| 🧠 | **ADAS & Autonomous Vehicles** *(placeholder — add your link)* | Automotive AI |
| 🔧 | **Embedded Systems for Automotive** *(placeholder — add your link)* | Embedded Systems |

---

## 📊 GitHub Stats

<div align="center">

<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=ayman-adriouech&show_icons=true&theme=tokyonight&bg_color=0D1117&border_color=0F6E56&title_color=0F6E56&icon_color=185FA5&text_color=ffffff&hide_border=false&border_radius=10&count_private=true" alt="GitHub Stats" />
    </td>
    <td>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ayman-adriouech&layout=compact&theme=tokyonight&bg_color=0D1117&border_color=0F6E56&title_color=0F6E56&text_color=ffffff&hide_border=false&border_radius=10" alt="Top Languages" />
    </td>
  </tr>
</table>

[![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=ayman-adriouech&theme=tokyo-night&custom_title=Contribution%20Activity&bg_color=0D1117&color=0F6E56&line=185FA5&point=0F6E56)](https://github.com/ayman-adriouech)

</div>

---

## 🌐 Languages

| Language | Level |
|----------|-------|
| 🇲🇦 Arabic | Native |
| 🇫🇷 French | C1 — Advanced |
| 🇬🇧 English | B2 — Upper Intermediate |
| 🇪🇸 Spanish | A2 — Beginner |

---

## 📫 Let's Connect

<div align="center">

<a href="https://www.linkedin.com/in/ayman-adriouech">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0F6E56?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="mailto:ayman.adriouech@ueuromed.eidia.org">
  <img src="https://img.shields.io/badge/Email-Get%20In%20Touch-185FA5?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<br/><br/>

> 💼 *Open to internships in Robotics, Automotive Engineering & Embedded AI*

</div>

---

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,3,5,30&height=120&section=footer&text=Thanks%20for%20visiting!&fontSize=40&fontColor=fff&animation=fadeIn" width="100%"/>

<div align="center">

**Made with ❤️ by Ayman ADRIOUECH | Morocco 🇲🇦**

</div>
