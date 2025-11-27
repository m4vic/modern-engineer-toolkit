# 🤖 Robotics Roadmap  
*Modern Engineer Toolkit — Robotics Track*

A modern, simulation-first roadmap for mastering robotics: ROS2, manipulation, motion planning, SLAM, computer vision, autonomous systems, and robot learning.

---

## ⚡ Quick Navigation

- **[High-Level Roadmap](#-high-level-roadmap)**
- **[Overview](#-overview)**
- **[Prerequisites](#-prerequisites)**
- **[Phase 0 — Foundation](#-phase-0--foundation-12-months)**
- **[Phase 1 — Beginner Robotics](#-phase-1--beginner-robotics-23-months)**
- **[Phase 2 — Intermediate Robotics](#-phase-2--intermediate-robotics-36-months)**
- **[Phase 3 — Advanced Robotics](#-phase-3--advanced-robotics-612-months)**
- **[Phase 4 — Specialization](#-phase-4--specialization-year-2)**
- **[Projects](#-projects-beginner--advanced)**
- **[Suggested Timeline](#-suggested-timeline)**
- **[Cross-links](#-cross-links)**

---

## 🗺 High-Level Roadmap
flowchart TD

A[Phase 0: Foundation<br/>Math • Physics • Programming • Electronics] --> B[Phase 1: Beginner Robotics<br/>Kinematics • Mobile Robots • Simulation]

B --> C[Phase 2: Intermediate Robotics<br/>ROS2 • Motion Planning • Manipulation • Perception]

C --> D[Phase 3: Advanced Robotics<br/>SLAM • Navigation • RL • High-Fidelity Simulation]

D --> E[Phase 4: Specialization<br/>Manipulation • Autonomy • Vision • UAVs • Industrial Robotics]

E --> F[Year 2+: Research & Industry<br/>Certifications • Open-Source • Publications]


## 🧭 Overview  
Robotics integrates **mechanics**, **electronics**, **real-time systems**, **control theory**, **simulation**, and **AI-driven perception & planning**.

This roadmap progresses from prerequisites → beginner → intermediate → advanced → specialization.

Cross-linked with:

- [Fundamentals](../Fundamentals/README.md)
- [Machine Learning](../Machine-Learning/README.md)
- [Deep Learning](../Deep-Learning/README.md)
- [GenAI / LLMs](../GenAI/README.md)
- [Quant](../Quant/README.md)
- [AGI](../AGI/README.md)

---

## 📘 Prerequisites  
*All foundational math, physics, and programming are handled in:  
➡️ [Fundamentals](../Fundamentals/README.md)*

- Linear algebra, calculus, probability  
- Classical mechanics  
- Python + C++ basics  
- Electronics basics  

---

# 🛠️ Phase 0 — Foundation (1–2 Months)

### Mathematics & Physics Resources

| Resource | Type | Cost | Link |
|---------|------|------|------|
| Khan Academy Physics | Course | Free | https://www.khanacademy.org/science/physics |
| Khan Academy Linear Algebra | Course | Free | https://www.khanacademy.org/math/linear-algebra |
| 3Blue1Brown Linear Algebra | Videos | Free | https://www.3blue1brown.com/topics/linear-algebra |
| MIT OCW: Classical Mechanics | Course | Free | https://ocw.mit.edu |

### Programming & Electronics Resources

| Resource | Type | Cost | Link |
|---------|------|------|------|
| Arduino Official Channel | YouTube | Free | https://www.youtube.com/c/Arduino |
| SparkFun Electronics | Tutorials | Free | https://www.youtube.com/c/SparkFun |
| Adafruit Industries | Tutorials | Free | https://www.youtube.com/c/AdafruitIndustries |
| Python (W3Schools) | Web Tutorial | Free | https://www.w3schools.com/python |
| C++ Basics | Web | Free | Multiple free sources |

### Hardware Introduction

| Resource | Type | Focus | Link |
|---------|------|--------|------|
| James Bruton | YouTube | DIY robots, mechanisms | https://www.youtube.com/c/JamesBruton |
| DroneBot Workshop | YouTube | Arduino, Pi, sensors | https://www.youtube.com/c/Dronebotworkshop |
| How to Mechatronics | YouTube | Arduino + robotics | https://www.youtube.com/c/HowToMechatronics |
| Jeremy Fielding | YouTube | Motors, actuators | https://www.youtube.com/c/JeremyFielding |

---

# 🚦 Phase 1 — Beginner Robotics (2–3 Months)

### What you learn  
- Basic kinematics  
- Mobile robots  
- Sensors  
- First simulations  

### Free University Courses

| Course | Provider | Level | Link |
|--------|----------|--------|------|
| MIT 2.12: Intro to Robotics | MIT OCW | Beginner | https://ocw.mit.edu/courses/2-12-introduction-to-robotics-fall-2005/ |
| Stanford CS223A | Stanford SEE | Beginner | https://see.stanford.edu/course/cs223a |
| Hello Real World with ROS | Delft/edX | Beginner | https://www.edx.org/learn/robotics/delft-university-of-technology-hello-real-world-with-ros-robot-operating-system |

### YouTube Channels

| Channel | Focus | Subs |
|--------|--------|------|
| James Bruton | DIY robotics | 1.38M |
| Jeremy Fielding | Motors & actuators | 1.14M |
| SparkFun | Sensors | 242K |
| Adafruit | Electronics | 460K |

### Simulation Platforms

| Platform | Features | Link |
|----------|----------|------|
| Webots | Open-source, ideal for beginners | https://cyberbotics.com |
| Gazebo | Physics + ROS integration | https://gazebosim.org |
| CoppeliaSim | Multi-robot physics | https://www.coppeliarobotics.com |

---

# 🧩 Phase 2 — Intermediate Robotics (3–6 Months)

### What you learn  
- ROS / ROS 2  
- Manipulators, kinematics/dynamics  
- Motion planning  
- Basic perception  

### Free Advanced Courses

| Course | Provider | Link |
|--------|----------|------|
| Programming for Robotics (ROS) | ETH Zürich | https://rsl.ethz.ch/education-students/lectures/ros.html |
| MIT Robotic Manipulation (6.4210) | MIT | https://ocw.mit.edu/courses/6-4210-robotic-manipulation-fall-2022/ |
| Autonomous Mobile Robots | ETH/edX | edX platform |

### ROS & Development Resources

| Resource | Type | Link |
|----------|------|------|
| ROS Docs | Official | https://www.ros.org |
| ROS2 Docs | Official | https://docs.ros.org |
| The Construct | Courses | https://www.theconstruct.ai |
| Mastering Gazebo | Course | The Construct |
| ROS2 Tutorials Repo | GitHub | https://github.com/sagar16812/Getting-Started-with-ROS2-A-Tutorial-Series |

### Key GitHub Repositories

| Repo | Purpose | Link |
|------|----------|------|
| awesome-robotics | Curated list | https://github.com/search?q=awesome-robotics |
| awesome-robotics-projects | Open-source robots | https://github.com/mjyc/awesome-robotics-projects |
| navigation2 | ROS2 navigation | https://github.com/ros-planning/navigation2 |
| moveit | Motion planning | https://github.com/moveit/moveit |
| librealsense | Depth cameras | https://github.com/IntelRealSense/librealsense |
| matlab-robotics | MATLAB robotics | https://github.com/mathworks-robotics/awesome-matlab-robotics |

---

# 🧠 Phase 3 — Advanced Robotics (6–12 Months)

### What you learn  
- Full autonomy stack  
- SLAM, mapping, localization  
- Reinforcement learning for control  
- High-fidelity simulation  

### Advanced Courses

| Course | Provider | Link |
|--------|----------|------|
| MIT MicroMasters in Robotics | MIT/edX | edX |
| SLAM & Navigation (ROS2) | ROS | https://docs.ros.org/humble/p/nav2/ |
| RL for Robotics | Various | Multiple |
| OpenCV University Bootcamps | OpenCV | https://opencv.org/university/free-courses/ |

### Specialized Topics

#### Computer Vision
- OpenCV University bootcamps  
- PyImageSearch CV crash course  
- YOLOv8 (Ultralytics)

#### Deep Learning & Perception  
- PyTorch, TensorFlow  
- OpenCV DNN module  

#### SLAM Tools  
- SLAM Toolbox  
- ORB-SLAM3  
- Hector SLAM  

---

# 🦾 Phase 4 — Specialization (Year 2+)

### Paid Certifications

| Certification | Provider | Focus |
|---------------|----------|--------|
| Udacity Robotics Nanodegree | Udacity | ROS, Gazebo, autonomy |
| FANUC (Operator/Technician) | FANUC | Industrial robotics |
| CIRP | ATMAE | Robot programming basics |
| KUKA College | KUKA | KUKA programming |

### Specialization Areas

#### Manipulation  
- MIT 6.4210  
- MoveIt tutorials  
- Dexterous hand research  

#### Humanoids & Legged Robotics  
- Berkeley Humanoid Lite  
- Boston Dynamics research papers  

#### Autonomous Vehicles  
- ETH Mobile Robots  
- TurtleBot3 + ROS2  
- NASA Open Source Rover  

---

# 🧪 Projects (Beginner → Advanced)

### Beginner  
- Line follower  
- Obstacle avoider  
- Differential drive simulation  
- Basic IK robot arm  

### Intermediate  
- ROS2 mobile robot  
- LIDAR mapping  
- MoveIt pick-and-place  
- Vision-based tracking  

### Advanced  
- Full SLAM + Navigation2 pipeline  
- Quadruped gait controller  
- Vision-language robotic agent  
- Drone autonomy (PX4 + Gazebo)  

---

# 📅 Suggested Timeline

### Months 1–2: Foundations  
- Python/C++ basics  
- Arduino basics  
- Simple simulations  

### Months 3–4: Beginner  
- MIT/Stanford courses  
- Mobile robot simulation  
- Kinematics basics  

### Months 5–6: ROS2 + Kinematics  
- Delft ROS course  
- Navigation basics  
- Full robot build in simulation  

### Months 7–12: Specialization  
Pick 1: manipulation, autonomy, vision, UAVs  

### Year 2+  
- Certifications  
- Open-source contributions  
- Research projects  

---

# 🧩 Cross-links  
- Math/Physics → [Fundamentals](../Fundamentals/README.md)  
- ML for perception → [Machine Learning](../Machine-Learning/README.md)  
- DL for vision → [Deep Learning](../Deep-Learning/README.md)  
- LLM robotics → [GenAI](../GenAI/README.md)

---

# ✔️ End of Robotics Roadmap  
*Part of the Modern Engineer Toolkit*

