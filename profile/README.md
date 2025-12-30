# 🏠 Inha-United

**Team Inha-United** is a research-driven robotics team formed by four laboratories at Inha University, Korea.  
We integrate expertise in SLAM, robot learning, multimodal perception, and large language models into unified service-robot systems for dynamic domestic environments.  
Our main platform is the **RB-Y1 humanoid robot**, supporting robust object manipulation, semantic spatial reasoning, and LLM-guided behavior execution for RoboCup@Home Open Platform League.

🌐 [Team Website](https://inha-united.github.io/Home2026/)  
📧 Corresponding Emails: yg.cho@inha.ac.kr, iwshim@inha.ac.kr, junwoo@inha.ac.kr, wjahn@inha.ac.kr  

---

## Team Description Papers
- **Team Description Paper 2026** [PDF](link-to-paper)
---

## Publications
- Autonomous Navigation using Deep Reinforcement Learning  
- Human-Robot Interaction: Social Behavior in Service Robots  
- 3D Mapping and Localization for Indoor Environments  

*(Links to PDFs can be added if available)*

---

## System Overview

### Hardware Setup
- **Robot Platform:** RB-Y1 humanoid robot  
- **Main Computer:** Jetson AGX Orin  
- **Perception Computer:** Jetson Thor  
- **Cameras:** Realsense D435f (head), Realsense D405 (arms)  
- **LiDAR:** Livox MID-360 for precise depth sensing  
- **Actuators:** Dual arms with grippers, differential-drive mobile base  
- **Applications:** Reception, person guidance, object delivery, grocery storing, restaurant serving

### Software Framework
- **Mission Handler:** Receives multimodal inputs (speech, vision, joint states) and dispatches tasks  
- **Core Capability Stacks:**  
  1. **Mapping and Navigation:** Topometric 2D–3D maps, SLAM, dynamic obstacle handling  
  2. **Manipulation:** Object pose estimation, grasp execution, motion planning  
  3. **Human–Robot Interaction:** Speech recognition (Whisper-v3), gesture recognition, human pose estimation, LLM-guided behavior trees  
- **Reusable Modules:** Each mission combines modules from all three stacks for flexible task execution  

---

## Robot Platforms
- **Social Robots:** Neubie, RB-Y1  
- **Field Robots:** Dual-Armed Tracer, GO2, Scout-Mini, Rover  

---

## ROS Packages

### ROS1
- `inha_quiz` – Quiz-based human-robot interaction  
- `inha_speech` – Speech recognition and synthesis  
- `inha_vision` – Computer vision algorithms  
- `inha_navigation` – Navigation stack  
- `inha_behavior` – Behavior control  
- `inha_moveit` – Manipulation planning  
- `inha_launchfiles` – Launch scripts and configs  

### ROS2
- `iu_behavior` – ROS2 behavior nodes  
- `iu_navigation` – ROS2 navigation stack  
- `iu_hri` – Human-robot interaction modules  
- `iu_vision` – Computer vision for ROS2  
- `iu_world` – Simulation and world description  
- `iu_bringup` – Robot initialization and launch  
- `iu_manipulator` – Manipulation services and actions  
- `iu_description` – URDF and robot description  
- `iu_simulation` – Gazebo simulation setup  
- `iu_agent` – AI/learning agent modules  
- `iu_learning` – Learning algorithms  

---

## Awards

### RoboCup@Home
- **Salvador 2025** – 7th Place  
- **Eindhoven 2024** – 11th Place  
- **Bordeaux 2023** – 9th Place  
- **Bangkok 2022** – 3rd Place  

### Korean Robotics Competitions
- 2025 – 1st Place 🥇  
- 2024 – 1st Place 🥇  
- 2023 – 1st Place 🥇  
- 2022 – 1st Place 🥇  
- 2021 – 2nd Place 🥈  
- 2020 – 3rd Place 🥉  

---

## Team Members
- Minho Lee  
- Dongjin Cho  
- Jungtae Kim  
- Gunwoo Park  
- Jiyun Kim  
- Jihyun Han  
- Sanghyun Lee  
- Wonhyuk Jung  
- Yonggun Cho  
- Inwook Shim  
- Junwoo Jang  
- Woojin Ahn  

---

## Links
- 🌐 [Team Website](https://inha-united.github.io/Home2026/)  
- 📧 Email: equipe.inhaunited@gmail.com  
- 🐦 [Twitter](https://twitter.com/inhaunited)  
- 🐙 [GitHub](https://github.com/inha-united)  

