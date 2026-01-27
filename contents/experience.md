[//]: # (### **家庭服务机器人系统研发**  )

[//]: # (**September 2024 – May 2025 | TJ-ARK战队, 同济大学**  )

[//]: # (*核心研发成员（视觉与决策系统）*)

[//]: # ()
[//]: # (主导开发了基于多模态感知的机器人智能决策系统，为战队在2025年RoboCup@Home赛事中赢得全国冠军提供关键技术支撑。)

[//]: # ()
[//]: # (#### **Key Contributions:**)

[//]: # (- **模型训练流水线**：构建端到端的目标检测模型训练流水线，集成自动化数据采集、增强与评估，显著提升模型迭代效率与检测精度。)

[//]: # (- **智能决策系统**：设计并实现基于视觉反馈的层次化决策系统，融合实时场景理解与任务规划，有效提升机器人在动态环境中的任务完成率。)

[//]: # (- **团队与技术建设**：作为技术骨干，负责ROS及机器人技术培训，系统提升团队研发能力；主导完善战队代码仓库，保障技术方案的快速迭代与稳定部署。)

[//]: # ()
[//]: # (---)

[//]: # ()
[//]: # (### **自主水下航行器（AUV）系统研发**  )

[//]: # (**March 2023 – June 2024 | 水下机器人创新实验室, 西北工业大学**  )

[//]: # (*项目负责人 / 全栈工程师*)

[//]: # ()
[//]: # (从零主导实验室首型模块化AUV的研制，完成从系统架构、软硬件开发到集成测试的全流程，实现了支持单机作业与多机协同的航行器平台。)

[//]: # ()
[//]: # (#### **Key Contributions:**)

[//]: # (- **系统架构设计**：基于ROS设计分层软件架构，实现感知-决策-控制等核心模块解耦，并通过硬件抽象层统一设备接口，提升系统可扩展性与调试效率。)

[//]: # (- **硬件平台实现**：主导硬件系统设计，涵盖耐压舱体、推进系统、传感器集群及通信链路，成功迭代出A型（水下干预）与B型（水面编队）两款变结构航行器。)

[//]: # (- **核心算法研发**：)

[//]: # (  - 提出基于运动学反演的水下目标检测与定位方法，在低可见度环境中实现目标精准识别与定位。)

[//]: # (  - 设计基于虚拟领航者-跟随者的分布式编队控制算法，实现多AUV的稳定队形保持与协同导航。)

[//]: # (- **工程落地与交付**：建立完整的集成测试流程，主持从单元测试到开放水域实机部署的全周期验证。成果产出包括优秀毕业论文、一项发明专利、一篇在审SCI论文及全套技术文档与代码仓库。)

[//]: # ()
[//]: # (---)

[//]: # ()
[//]: # (### **智能越野小车系统研发**  )

[//]: # (**October 2021 – July 2023 | 智能车基地, 西北工业大学**  )

[//]: # (*极速越野组队长*)

[//]: # ()
[//]: # (负责整车感知、导航与控制算法的研发与集成，带领团队获得第十八届全国大学生智能汽车竞赛西部赛区二等奖。)

[//]: # ()
[//]: # (#### **Key Contributions:**)

[//]: # (- **视觉感知系统**：设计基于大津法（Otsu）的自适应阈值视觉路径识别系统，在复杂光照条件下实现高鲁棒性的赛道特征提取。)

[//]: # (- **多传感器融合导航**：开发融合IMU（经互补滤波）与GNSS的紧耦合导航算法，实现车辆在高速越野场景下的精准位姿估计。)

[//]: # (- **运动控制算法**：实现并对比优化了经典PID与模糊PID控制算法，应用于车辆方向与速度控制，以应对高速越野的动态需求。)

[//]: # (- **系统集成与沉淀**：完成系统集成与竞赛参数调优，申请软件著作权一项，并建立车队技术文档与调试手册。)

### **Household Service Robot System Development**  
**September 2024 – May 2025 | TJ-ARK Team, Tongji University**  
*Core R&D Member (Vision & Decision-Making System)*

Spearheaded the development of an intelligent robot decision-making system based on multimodal perception, providing key technical support for the team to win the National Championship in the 2025 RoboCup@Home competition.

#### **Key Contributions:**
- **Model Training Pipeline:** Built automated training pipeline for object detection models, integrating automated data collection and augmentation, significantly accelerating model iteration and improving detection accuracy.
- **Intelligent Decision-Making System:** Designed and implemented a hierarchical decision-making system based on visual feedback, fusing real-time scene understanding with task planning to effectively increase the robot's task completion rate in dynamic home environments.
- **Team & Tech Infrastructure:** As a key technical member, conducted ROS and robotics training to systematically enhance the team's R&D capabilities. Led the improvement of the team's code repository to ensure rapid iteration and stable deployment of technical solutions.

<div align="center">
  <img src="/static/assets/img/robocup.png" alt="Our Home Service Robot" width="400" />
</div>

---

### **Autonomous Underwater Vehicle (AUV) System Development**  
**March 2023 – June 2024 | Underwater Robotics Innovation Lab, Northwestern Polytechnical University**  
*Project Lead / Full-Stack Engineer*

Led the full-cycle development of the lab's first modular AUV platform from scratch, encompassing system architecture, hardware/software development, and integration testing. The platform supports both solo missions and multi-AUV cooperative tasks.

#### **Key Contributions:**
- **System Architecture Design:** Architected a layered software framework based on ROS, decoupling core modules (perception, decision-making, guidance, navigation and control), enhancing system scalability and debugging efficiency.
- **Hardware Platform Implementation:** Led the hardware system design, including the pressure-resistant hull, propulsion system, sensor suite, power management, and communication links. Successfully delivered two variant prototypes: Type A (for underwater intervention) and Type B (for surface formation).
- **Core Algorithm Development:**
  - Proposed a kinematics-inversion-based method for underwater target detection and localization, enabling accurate detection and positioning in low-visibility conditions.
  - Designed a distributed formation control algorithm based on the virtual leader-follower approach, achieving stable formation keeping and cooperative navigation for multiple AUVs.
- **Engineering Delivery & Validation:** Established a complete integration and testing pipeline, overseeing validation from unit testing to open-water field deployment. Deliverables included an outstanding undergraduate thesis, one invention patent, one SCI journal paper (under review), and comprehensive technical documentation with code repository.

<div align="center">
  <img src="/static/assets/img/auv.png" alt="Our AUV" width="400" />
</div>

---

### **Intelligent Off-Road Vehicle System Development**  
**October 2021 – July 2023 | Intelligent Vehicle Base, Northwestern Polytechnical University**  
*Team Captain, High-Speed Off-Road Group*

Responsible for the R&D and integration of perception, navigation, and control algorithms for an autonomous off-road vehicle. Led the team to win the 2nd Prize in the Western China Division of the 18th National University Intelligent Car Competition.

#### **Key Contributions:**
- **Vision-Based Perception System:** Designed a visual path recognition system utilizing the Otsu method for adaptive thresholding, achieving robust lane feature extraction under challenging lighting conditions.
- **Multi-Sensor Fusion Navigation:** Developed a tightly coupled navigation algorithm fusing IMU data (processed with complementary filtering) and GNSS signals, enabling precise pose estimation for high-speed off-road driving.
- **Motion Control Algorithms:** Implemented and comparatively optimized classical PID and fuzzy PID controllers for vehicle steering and speed control to meet the dynamic demands of high-speed off-road scenarios.
- **System Integration & Knowledge Management:** Completed system integration and competition parameter tuning. Filed one software copyright and established team technical documentation and debugging manuals.

<div align="center">
  <img src="/static/assets/img/car.png" alt="Our Car" width="400" />
</div>