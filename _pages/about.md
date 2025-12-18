---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

👋 **Hi there! I am Junlin (Leo) Lyu.**

I am a Graduate Researcher and Master's student at Columbia University in the city of New York, where I work in the [Creative Machines Lab](https://www.creativemachineslab.com) under the supervision of [Prof. Hod Lipson](https://www.hodlipson.com).

## 🤖 Research Interests

My research revolves around **robotics** and **machine learning** with key interests in:

* Humanoid Robot (Face Robot, Robot Arm)
* Robot Learning (Imitation Learning)
* Self-supervised Learning and Self-modeling robots

## 🌟 Research and Highlights

## Eye, Robot: A Vision-Language-Action Model for Personalized, Realistic Gaze 
![Rehab Robot](/images/eye_robot/eye_robot_gif.gif){: .align-right width="350px"}

We proposed a novel **Vision-Language-Action (VLA)** architecture that decouples reasoning (VLM) from motor control to synthesize realistic humanoid gaze. I engineered an automated pipeline using Google MediaPipe to create a custom dataset of 52 blendshape parameters and trained a conditional Action Transformer to predict 11-DoF joint trajectories. The system was validated in a high-fidelity MuJoCo simulation and achieved real-time interaction (>60Hz) with human-like attention switching.


_Paper Coming Soon !!!_
<div style="clear:both;"></div>

## Reverse Joint Quadruped Robot       
![Rehab Robot](/images/RRR_ankles/ankle_gif.gif){: .align-right width="350px"}

I designed and fabricated a bio-inspired, parallel-mechanism quadruped robot. To achieve stable locomotion, I built high-fidelity simulation environments in MuJoCo and PyBullet and implemented **Deep Reinforcement Learning (PPO)**. The optimized gait control policies enabled the robot to navigate uneven terrain and reach a maximum speed of 39.6 cm/s in the real world.

_**Junlin Lyu**_

[[Video Link]](/files/ankle_paper.pdf)
<div style="clear:both;"></div>

## Design and Modeling of a 3-RRR Parallel Ankle Rehabilitation Robot 
![Rehab Robot](/images/RRR_ankles/ankle_gif.gif){: .align-right width="350px"}

We developed a wearable ankle rehabilitation robot using a 3-RRR spherical parallel mechanism. We complete the engineering pipeline from mechanical design in SolidWorks, 3D-printed prototyping, Lagrangian dynamics modeling, to MATLAB simulation of compliance-modulated PID control.

_**Junlin Lyu**\*, Siyuan Zhang\*, Yufei Zhang\*, Sunil K. Agrawal_ (* Equal contribution) 

[[Paper]](/files/ankle_paper.pdf)
<div style="clear:both;"></div>


## 👨‍🏫 Teaching

**Teaching Assistant, Robotics Studio** (Columbia University, Fall 2025)

*Instructor: Prof. Hod Lipson*
* Mentored students through the full robot development lifecycle, from CAD design and 3D printing to achieving stable walking locomotion in physical prototypes.
* Developed course materials and GitHub repositories, creating technical tutorials on **MuJoCo simulation and parameter optimization algorithms**. [[Mujoco Introduction repositories]](https://github.com/leolyu-web/Robotics_studio_Mujoco_Intro)
* Instructed on **Deep Reinforcement Learning**, creating presentation class materials and GitHub repositories for training custom policies using Gymnasium and Stable-Baselines3 for their own robot. [[Reinforcement Learning Mujoco repositories]](https://github.com/leolyu-web/Robotics_studio_RL_PPO)

## 🛠️ Technical Skills

* **Programming & Development Tools:** Python, C/C++, MATLAB, LaTeX, Linux, Git, Xcode, VScode
* **Robotics & AI:** ROS2, MuJoCo, Isaac Lab, PyBullet, Unreal Engine, PyTorch, Simulink
* **Design & Engineering:** Fusion 360,SolidWorks, AutoCAD, FEA (FEMM)
* **Spoken Languages:** English, Mandarin, German

---

Feel free to explore my website to learn more about my work!