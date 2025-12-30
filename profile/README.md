# Hi There  👋

**We are Inha-United** ,multi-lab research group (RCV Lab, SPARO Lab, Artemis Lab, RILS Lab) at Inha University.

🌐 [Team Website](https://inha-united.github.io/Home2026/)  
📄 [Team Description Papers][PDF](link_to_pdf)
📧 Corresponding Emails: yg.cho@inha.ac.kr, iwshim@inha.ac.kr, junwoo@inha.ac.kr, wjahn@inha.ac.kr  

**Publications**  
- Autonomous Navigation using Deep Reinforcement Learning  
- Human-Robot Interaction: Social Behavior in Service Robots  
- 3D Mapping and Localization for Indoor Environments  

*(Links to PDFs can be added if available)*

**System Overview**

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
- `inha_quiz` – Quiz-based human-robot interaction  
- `inha_speech` – Speech recognition and synthesis  
- `inha_vision` – Computer vision algorithms  
- `inha_navigation` – Navigation stack  
- `inha_behavior` – Behavior control  
- `inha_moveit` – Manipulation planning  
- `inha_launchfiles` – Launch scripts and configs  

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

**Links**  
- 🌐 [Team Website](https://inha-united.github.io/Home2026/)  
- 📧 Email: equipe.inhaunited@gmail.com  
- 🐦 [Twitter](https://twitter.com/inhaunited)  
- 🐙 [GitHub](https://github.com/inha-united)  
