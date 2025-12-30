**Hi There 👋**

**We are Inha-United**, multi-lab research group (RCV Lab, SPARO Lab, Artemis Lab, RILS Lab) at Inha University.

![photo](https://github.com/inha-united-athome/.github/blob/main/profile/inha_united.jpg)



🌐 [Team Website](https://inha-united.github.io/Home2026/)  
📄 [Team Description Paper 2026 PDF](https://github.com/inha-united-athome/.github/blob/main/profile/Inha_United_Team_Description_Paper.pdf)

**System Overview**
![System Overview](https://github.com/inha-united-athome/.github/blob/main/profile/system_overview.jpg)



**Hardware Setup**  
- **Robot Platform:** RB-Y1 humanoid robot  
- **Main Computer:** Jetson AGX Orin  
- **Perception Computer:** Jetson Thor  
- **Cameras:** Realsense D435f (head), Realsense D405 (arms)  
- **LiDAR:** Livox MID-360 for precise depth sensing  
- **Actuators:** Dual arms with grippers, differential-drive mobile base  
- **Applications:** Reception, person guidance, object delivery, grocery storing, restaurant serving

**Software Framework**  
- **Mission Handler:** Receives multimodal inputs (speech, vision, joint states) and dispatches tasks  
- **Core Capability Stacks:**  
  1. **Mapping and Navigation:** Topometric 2D–3D maps, SLAM, dynamic obstacle handling  
  2. **Manipulation:** Object pose estimation, grasp execution, motion planning  
  3. **Human–Robot Interaction:** Speech recognition (Whisper-v3), gesture recognition, human pose estimation, LLM-guided behavior trees  
- **Reusable Modules:** Each mission combines modules from all three stacks for flexible task execution  

**ROS Packages**
- [`inha_bringup`](https://github.com/inha-united-athome/inha_bringup) – Robot initialization and launch  
- [`inha_manipulator`]([https://github.com/inha-united-athome/inha_manipulator) – Manipulation services and actions  
- [`inha_vision`](https://github.com/inha-united-athome/inha_vision) – Computer vision modules  
- [`inha_hri`](https://github.com/inha-united-athome/inha_hri) – Human-robot interaction modules  
- [`inha_navigation`](https://github.com/inha-united-athome/inha_navigation) – Navigation stack  
- [`inha_behavior`](https://github.com/inha-united-athome/inha_behavior) – Behavior control

**Team Members**  
- Minho Lee  
- Dongjin Cho
- Minho Lee 
- Jungtae Kim  
- Gunwoo Park  
- Jihyun Han  
- Sanghyun Lee  
- Wonhyuk Jung
- GiHyeok Kwon
- Yonggun Cho  
- Inwook Shim  
- Junwoo Jang  
- Woojin Ahn  

