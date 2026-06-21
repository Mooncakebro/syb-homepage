### **Curiosity-Driven Agentic Pre-training & Continual Learning (Ongoing)**  
**May 2026 – Present | AIR, Tsinghua University**  
*Research Intern (Streaming Memory Compression)*

Co-architect an agentic pre-training paradigm for curiosity-driven autonomous exploration, enabling agents to distill underlying mechanisms beyond statistical data distributions (e.g., causal chains). Design the Memory System within the Agent-Memory-World Model architecture, which manages the full lifecycle of streaming memory (formation, aggregation, and injection) to enable lifelong adaptation.

#### **Key Contributions:**
- **Streaming Memory Aggregation:** Develop a memory post-processing module inspired by the [delta-mem](https://arxiv.org/abs/2605.12357) to aggregate compressed representations into fixed-size states, preventing the linear growth of memory tokens.
- **Unified Actor-Compressor Architecture:**  Design a novel architecture unifying the Actor and Compressor. It introduces an RNN-style memory state at each LLM layer, utilizing dedicated read/write mechanisms and cross-attention for layer-wise memory injection.

<div align="center">
  <img src="https://github.com/Mooncakebro/syb-homepage/blob/main/static/assets/img/agent_memory.png?raw=true" 
       alt="GUI Agent Framework" 
       width="800" />
</div>

---


### **Industrial Aluminum Processing VLA System Development (Ongoing)**  
**March 2026 – Present | Robot and AI Lab, Tongji University**  
*Core R&D Member (VLA & Lifelong Learning Mechanism)*

Contribute to the development of a Vision-Language-Action (VLA) model for industrial aluminum sheet processing, built upon the LeRobot and StarVLA frameworks. Pioneer lifelong imitation learning paradigms to enable continuous, boundary-free skill acquisition in dynamic manufacturing environments.

#### **Key Contributions:**
- **VLA System Architecture:** Engineer a VLA model for industrial manipulation, leveraging the LeRobot and StarVLA frameworks to seamlessly bridge high-level semantic instructions with low-level robotic control policies.
- **Causal-Inspired Feature Enhancement Module:** Design a feature enhancement module inspired by the Front-Door Criterion in causal inference. Implement an attention-based adaptive gating mechanism to facilitate interaction between visual & goal features (extracted via ResNet & CLIP) and semantic priors (from a frozen VLM), improving robustness in complex industrial scenes.
- **Lifelong Learning Mechanism:** Develop a lifelong imitation learning mechanism by adapting the [LEGION](https://www.nature.com/articles/s42256-025-00983-2) framework. Integrate a Dirichlet Process Mixture Model (DPMM) with a Variational Autoencoder (VAE) to build a high-level task encoder, enabling adaptive clustering of streaming tasks without predefined task boundaries and providing robust conditional representations for downstream decoder.

<!-- <div align="right">
  <img src="https://github.com/Mooncakebro/syb-homepage/blob/main/static/assets/gif/vla_demo.gif?raw=true" 
       alt="VLA demo on SO101 and Realman robot" 
       width="600" />
</div> -->

<div style="display: flex; align-items: center; justify-content: center; gap: 20px; flex-wrap: wrap;">
  <img src="https://github.com/Mooncakebro/syb-homepage/blob/main/static/assets/img/vla_framework.png?raw=true" 
       alt="Overall VLA structure" 
       style="height: 250px;" />
  <img src="https://github.com/Mooncakebro/syb-homepage/blob/main/static/assets/gif/vla_demo.gif?raw=true" 
       alt="VLA demo on SO101 and Realman robot" 
       style="height: 250px;" />
</div>

---

### **Household Service Robot System Development**  
**September 2024 – May 2025 | TJ-Ark Team, Tongji University**  
*Core R&D Member (Vision & Decision-Making System)*

Spearheaded the development of an intelligent robot decision-making system based on multimodal perception, providing key technical support for the team to win the National Championship in the 2025 RoboCup@Home competition.

#### **Key Contributions:**
- **Model Training Pipeline:** Built automated training pipeline for object detection models, integrating automated data collection and augmentation, significantly accelerating model iteration and improving detection accuracy.
- **Intelligent Decision-Making System:** Designed and implemented a hierarchical decision-making system based on visual feedback, fusing real-time scene understanding with task planning to effectively increase the robot's task completion rate in dynamic home environments.
- **Team & Tech Infrastructure:** As a key technical member, conducted ROS and robotics training to systematically enhance the team's R&D capabilities. Led the improvement of the team's code repository to ensure rapid iteration and stable deployment of technical solutions.

<div align="center">
  <img src="https://github.com/Mooncakebro/syb-homepage/blob/main/static/assets/img/robocup.png?raw=true" 
       alt="Our Home Service Robot" 
       width="1000" />
</div>

---

### **Autonomous Underwater Vehicle (AUV) System Development**  
**March 2023 – June 2024 | Underwater Robot Innovation Lab, Northwestern Polytechnical University**  
*Project Lead / Full-Stack Engineer*

Led the full-cycle development of the lab's first modular AUV platform from scratch, encompassing system architecture, hardware/software development, and integration testing. The platform supports both solo missions and multi-AUV cooperative tasks.

#### **Key Contributions:**
- **System Architecture Design:** Architected a layered software framework based on ROS, decoupling core modules (perception, decision-making, guidance, navigation and control, sensor and actuator), enhancing system scalability and debugging efficiency.
- **Hardware Platform Implementation:** Led the hardware system design, including the control system, sensor suite, propulsion system, power management, and communication links. Successfully delivered two variant prototypes: Type A (for underwater intervention) and Type B (for surface formation).
- **Core Algorithm Development:**
  - Proposed a kinematics-inversion-based method for underwater target detection and localization, enabling accurate detection and positioning in low-visibility conditions.
  - Designed a distributed formation control algorithm based on the virtual leader-follower approach, achieving stable formation keeping and cooperative navigation for multiple AUVs.
- **Engineering Delivery & Validation:** Established a complete integration and testing pipeline, overseeing validation from unit testing to open-water field deployment. Deliverables included an outstanding undergraduate thesis, one invention patent, one SCI journal paper (under review), and comprehensive technical documentation with code repository.

<div align="center">
  <img src="https://github.com/Mooncakebro/syb-homepage/blob/main/static/assets/img/auv.png?raw=true" 
       alt="Our AUV" 
       width="1000" />
</div>

<br>

<div align="center">
  <a href="https://www.bilibili.com/video/BV15ocLzWEuU/?spm_id_from=333.1387.homepage.video_card.click&vd_source=446263e471032186edf521695a9208be" target="_blank">
    <img src="https://github.com/Mooncakebro/syb-homepage/blob/main/static/assets/gif/auv.gif?raw=true" 
         alt="Click to watch the AUV experiment video on Bilibili" 
         width="800" 
         style="cursor: pointer; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.2);" />
    <br>
    <strong>▶️ Click to watch the AUV experiment footage on Bilibili</strong>
  </a>
</div>

---

### **Unmanned Off-Road Vehicle System Development**  
**October 2021 – July 2023 | Intelligent Vehicle Base, Northwestern Polytechnical University**  
*Team Captain, High-Speed Off-Road Group*

Responsible for the R&D and integration of perception, navigation, and control algorithms for an autonomous off-road vehicle. Led the team to win the 2nd Prize in the Western China Division of the 18th National University Smart Car Race.

#### **Key Contributions:**
- **Vision-Based Perception System:** Designed a visual path recognition system utilizing the Otsu method for adaptive thresholding, achieving robust lane feature extraction under challenging lighting conditions.
- **Multi-Sensor Fusion Navigation:** Developed a navigation algorithm fusing IMU data (processed with complementary filtering) and GNSS signals, enabling precise pose estimation for high-speed off-road driving.
- **Motion Control Algorithms:** Implemented and optimized classical PID and fuzzy PID controllers for vehicle steering and speed control to meet the dynamic demands of high-speed off-road scenarios.
- **System Integration & Knowledge Management:** Completed system integration and key parameter tuning. Filed one software copyright and established team technical documentation and debugging manuals.

<div align="center">
  <img src="https://github.com/Mooncakebro/syb-homepage/blob/main/static/assets/img/car.png?raw=true" 
       alt="Our Car" 
       width="1000" />
</div>

<br>

<div align="center">
  <a href="https://www.bilibili.com/video/BV1wAc7zuEUq/?spm_id_from=333.1387.homepage.video_card.click&vd_source=446263e471032186edf521695a9208be" target="_blank">
    <img src="https://github.com/Mooncakebro/syb-homepage/blob/main/static/assets/gif/car.gif?raw=true"
         alt="Click to watch the competition video on Bilibili" 
         width="800" 
         style="cursor: pointer; border-radius: 8px;" />
    <br>
    <strong>▶️ Click to watch the high-speed off-road testing footage on Bilibili</strong>
  </a>

[//]: # (  <p><em>High-Speed Off-Road Testing Footage</em></p>)
</div>

