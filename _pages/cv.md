---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Computer Science (Candidate)** — Peking University, Beijing, China — 2024–Present
  * School of Integrated Circuits
* **M.Sc. in Computer Science (Awarded with Distinction)** — University of Bristol, Bristol, UK — 2019–2020
  * School of Computer Science
* **B.Eng. in Intelligence Science and Technology** — Nankai University, Tianjin, China — 2014–2018
  * College of Computer Science and Control Engineering

Work Experience
======
* **Senior Research Engineer** — Beijing Institute for General Artificial Intelligence (BIGAI) — Apr. 2021 – Jul. 2024
  * National Key Laboratory for General Artificial Intelligence
  * Led development of computer vision-based object detection, segmentation, and semantic 3D map reconstruction
  * Contributed to motion generation for virtual humans performing daily activities
  * **Awarded Engineer of the Year**

* **Research Assistant** — Tianjin University — Jun. 2018 – Jun. 2019

Research Projects
======
* **A Learning-Free Method for Locomotion Mode Prediction by Terrain Reconstruction and Visual-Inertial Odometry**
  * Proposed D-VIO leveraging depth constraints for robust wearer pose estimation under foot-ground contact shocks
  * Constructed GPU-resident dense terrain map with real-time updates using planar primitives
  * Published in *IEEE TNSRE*, 2023

* **Self-Initialized Locomotion Mode Prediction with GPU-Free Terrain Reconstruction**
  * Developed cascaded LiDAR-Visual-Inertial coupling scheme for initialization under both stationary and walking conditions
  * Achieved GPU-free terrain reconstruction via polygon-based planar primitives, matching or exceeding GPU-dependent approaches
  * Under review at *IEEE TNSRE*

* **Bridging the Illumination Gap: Illumination-Robust Feature Extraction Enhanced by Relightable 3D Reconstruction**
  * Published at *2025 IEEE/ASME AIM Conference*

* **BioPIE: A Biomedical Protocol Information Extraction Dataset for High-Reasoning-Complexity Experiment Question Answering**
  * Manuscript in preparation for *EMNLP 2026*

Skills
======
* **Programming Languages:** C/C++, Python
* **Research Areas:** Computer Vision, Robotics, SLAM, Bipedal Robot, 3D Reconstruction
* **Frameworks & Tools:** PyTorch, ROS, OpenCV, CUDA

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Personal Interests
======
* Xiangsheng (Chinese Traditional Comic Dialogue)
* Photography
