# Awesome-Quadruped-with-Manipulator-Projects [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![Maintained](https://img.shields.io/badge/Maintained%3F-yes-brightgreen.svg)

## 🦾 Basic Info
This repository collects **academic papers and open-source projects** related to **quadruped robots equipped with manipulators (arms)**. The entries are categorized by **task type**, such as manipulation, locomotion, and whole-body control.

<!-- - 📌 **Real robot experiments** are highly preferred. -->
- 🌟 Papers or projects with **open-sourced code** are marked with a star.

Feel free to open a pull request for adding new papers, datasets, or codebases related to quadruped robots with arms.

---

## 📚 Table of Contents

- [Awesome-Quadruped-with-Arm-Learning](##awesome-quadruped-with-arm-learning)
  - [Whole-Body Control](##whole-body-control)
  - [Locomotion and Navigation](##objects-grasping)
  - [Arm Manipulation](##arm-manipulation)
  - [Sim-to-Real Transfer](##sim-to-real-transfer)
  - [Simulation Benchmarks](##simulation-benchmarks)
  - [Hardware Design](##hardware-design)
  - [Teleoperation and Human-Robot Interaction](##teleoperation-and-human-robot-interaction)
  - [Multimodal Perception and Learning](##multimodal-perception-and-learning)

---

## 🦿 With Whole-Body Control
- [Science Robotics 2025](https://www.science.org/doi/epdf/10.1126/scirobotics.adu3922) **Learning coordinated badminton skills for legged manipulators.** 
- [arXiv 2025.05](https://arxiv.org/abs/2505.20829) **Learning Unified Force and Position Control for Legged Loco-Manipulation.** [🌐Website](https://unified-force.github.io/) 
- [ICRA 2025](https://arxiv.org/abs/2411.06782) **## QuadWBG: Generalizable Quadrupedal Whole-Body Grasping.** [🌐Website](https://quadwbg.github.io/)
- [CoRL 2024](https://arxiv.org/abs/2407.10353) **UMI on Legs: Making Manipulation Policies Mobile with Manipulation-Centric Whole-body Controllers.** [🌐Website](https://umi-on-legs.github.io/), [🌟Code](https://github.com/real-stanford/umi-on-legs)
- [arXiv 2024.10](https://arxiv.org/abs/2410.00231) **Helpful DoggyBot: Open-World Object Fetching using Legged Robots and Vision-Language Models.** [🌐Website](https://helpful-doggybot.github.io/), [🌟Code](https://github.com/WooQi57/Helpful-Doggybot)
- [arXiv 2024.09](https://arxiv.org/abs/2409.19920) **Playful DoggyBot: Learning Agile and Precise Quadrupedal Locomotion.** [🌐Website](https://playful-doggybot.github.io/)
- [arXiv 2024.03](https://arxiv.org/abs/2403.17367v4) **RoboDuet: Whole-body Legged Loco-Manipulation with Cross-Embodiment Deployment.** [🌐Website](https://locomanip-duet.github.io/), [🌟Code](https://github.com/locomanip-duet/RoboDuet)
- [arXiv 2024.09](https://arxiv.org/abs/2409.16048) **Whole-body End-Effector Pose Tracking.** [🌐Website](https://leggedrobotics.github.io/wholebody-pose-control/)
- [ICRA 2024](https://arxiv.org/abs/2405.01402) **Learning Force Control for Legged Manipulation.** [🌐Website](https://tif-twirl-13.github.io/learning-compliance), [🌟Code](https://github.com/Improbable-AI/learning-compliance)
- [RAL 2024](https://arxiv.org/abs/2412.03012) **Learning Whole-Body Loco-Manipulation for Omni-Directional Task Space Pose Tracking with a Wheeled-Quadrupedal-Manipulator.** [🌐Website](https://clearlab-sustech.github.io/RFM_loco_mani/)
- [CoRL 2024](https://arxiv.org/abs/2403.16967) **Visual Whole-Body Control for Legged Loco-Manipulation.** [🌐Website](https://wholebody-b1.github.io/), [🌟Code](https://github.com/Ericonaldo/visual_wholebody)
- [arXiv 2024.10](https://arxiv.org/pdf/2410.05681) **Whole-Body Dynamic Throwing with Legged Manipulators.** 
- [ICRA 2024](https://arxiv.org/abs/2311.00112) **Hierarchical Optimization-based Control for Whole-body Loco-manipulation of Heavy Objects.** 
- [Autonomous Robots 2023](https://arxiv.org/abs/2203.01446) **RoLoMa: Robust Loco-Manipulation  for Quadruped Robots with Arms.**

---

## 🦿 Without Whole-Body Control
- [arXiv 2025.01](https://arxiv.org/abs/2501.09905) **SLIM: Sim-to-Real Legged Instructive Manipulation via Long-Horizon Visuomotor Learning.**
- [arXiv 2025.02](https://arxiv.org/abs/2502.10894) **Bridging the Sim-to-Real Gap for Athletic Loco-Manipulation.** [🌐Website](https://uan.csail.mit.edu/) 
- [arXiv 2025.02](https://arxiv.org/abs/2502.01546) **Dynamic object goal pushing with mobile manipulators through model-free constrained reinforcement learning.**
- [arXiv 2024.10](https://arxiv.org/abs/2410.06911) **Combining Planning and Diffusion for Mobility with Unknown Dynamics.** [🌐Website](https://yravan.github.io/plannerorderedpolicy/), [🌟Code](https://github.com/zt-yang/diffusion-ccsp)
- [arXiv 2025.02](https://arxiv.org/abs/2502.05271) **RobotMover: Learning to Move Large Objects From Human Demonstrations.** [🌐Website](https://easypapersniper.github.io/projects/robotMover/robotMover.html)
- [ECCV 2024](https://arxiv.org/abs/2405.01527) **Track2Act: Predicting Point Tracks from Internet Videos enables Generalizable Robot Manipulation.** [🌐Website](https://homangab.github.io/track2act/), [🌟Code](https://github.com/homangab/Track-2-Act/)
- [arXiv 2024.03](https://arxiv.org/pdf/2403.07563) **Learning Generalizable Feature Fields for Mobile Manipulation.** [🌐Website](https://geff-b1.github.io/)
- [arXiv 2024.11](https://arxiv.org/pdf/2411.15131) **WildLMa: Long Horizon Loco-Manipulation in the Wild.** [🌐Website](https://wildlma.github.io/)
- [ICRA 2025](https://arxiv.org/pdf/2402.11498) **Verifiably Following Complex Robot Instructions with Foundation Models.** [🌐Website](https://robotlimp.github.io/), [🌟Code](https://github.com/benedictquartey/robotlimp)
- [CoRL 2024](https://continual-mobile-manip.github.io/) **Continuously Improving Mobile Manipulation with Autonomous Real-World RL.** [🌐Website](https://geff-b1.github.io/)
- [RAL 2023](https://arxiv.org/abs/2304.00410) **Asc: Adaptive skill coordination for robotic mobile manipulation.** [🌐Website](https://adaptiveskillcoordination.github.io/)
- [ICRA 2024](https://arxiv.org/abs/2309.15459) **GAMMA: Graspability-Aware Mobile MAnipulation Policy Learning based on Online Grasping Pose Fusion.** [🌐Website](https://pku-epic.github.io/GAMMA/), [🌟Code](https://github.com/user432/gamma)



## 🐾 Locomotion and Navigation
- [RSS 2023] Learning Agile Locomotion for Quadruped with Arm Payloads.
- [NeurIPS 2022] Decoupling Base and Arm Dynamics for Stable Terrain Traversal.

---

## ✋ Arm Manipulation
- [ICRA 2024] ArmReach: Vision-based Object Grasping with a Quadruped Arm. [🌟Code](https://github.com/author/armreach)
- [arXiv 2025.03] Multi-DOF Manipulation from Quadruped Arm under Unknown Dynamics.

---

## 🌐 Sim-to-Real Transfer
- [CoRL 2024] Sim2QuadArm: Bridging Simulation and Reality for Arm-Leg Coordination. [🌟Code](https://github.com/author/sim2quadarm)
- [arXiv 2024.12] Domain Randomization for Dual-Motion Learning in Legged Robots.

---

## 🧪 Simulation Benchmarks
- [QuadrupedArmSim](https://github.com/example/quadrupedarmsim): Isaac Gym-based benchmark suite for quadruped-arm control tasks. [🌟Code](https://github.com/example/quadrupedarmsim)
- [PyBullet-QuadrupedArmEnv](https://github.com/example/pybullet-quadruped-arm-env)

---

## 🔧 Hardware Design
- [RA-L 2023] A Compact Arm Module for Unitree Quadrupeds.
- [ICRA 2025] Modular Mechanical Design for Low-Cost Quadruped Arms.

---

## 🎮 Teleoperation and Human-Robot Interaction
- [CHI 2025] Mixed Reality Interface for Teleoperating Quadruped Arms in Disaster Environments.
- [arXiv 2025.01] Gesture-based Control for Quadruped Manipulators.

---

## 🎯 Multimodal Perception and Learning
- [CVPR 2024] Learning to Fuse Vision and Proprioception for Object Manipulation in Quadrupeds.
- [ICLR 2025] Multi-View Learning for Contact-Rich Interaction on Quadruped Robots.

---

## 🤝 Contributing

We welcome contributions! Please submit a pull request with:
- Paper/project title
- Source or publication link
- Open-source code link (if available)
- Indicate if real robot experiments were performed

---

## 📜 License
MIT License

