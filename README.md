# Awesome-Computer-Vision-Warehouse-Sort-Systems

## Top Computer Vision Warehouse Sort Systems Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on 6-DoF Grasp Detection, Bin Picking & Cluttered Scene Understanding*

**Last updated: March 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Computer Vision Warehouse Sort Systems**. These tools enable robotic pickers to identify, grasp, and sort objects in highly cluttered environments—using 3D vision, pose estimation, and deep learning to guide grippers through dense bins of mixed SKUs.



**Examples** include Covariant, Dexterity, Berkshire Grey, Ambi Robotics, Plus One Robotics, Photoneo, OSARO, Fizyr, Mujin, and Knapp Pick-it-Easy (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, 6-DoF grasp detection, and open bin-picking simulation—ideal for robotics engineers, warehouse automation teams, and developers seeking transparent, vendor-independent vision systems.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Covariant](https://covariant.ai/)**

  AI-powered robotic picking platform for warehouse fulfillment. Uses deep learning for object recognition and grasp planning across variable SKUs, mixed cases, and irregular packaging.



- **[Dexterity](https://www.dexterity.ai/)**

  Full-stack robotic picking systems for warehouse and logistics. Features dual-arm robots with tactile sensing for handling diverse objects in cluttered environments.



- **[Berkshire Grey](https://www.berkshiregrey.com/)**

  Intelligent robotic automation for fulfillment operations. Features AI-powered piece picking, sortation, and packing systems for e-commerce and retail.



- **[Ambi Robotics](https://ambirobotics.com/)**

  AI-powered robotic sorting systems using AmbiSort platform. Features suction-based gripping with deep learning for parcel and piece handling.



- **[Plus One Robotics](https://plusonerobotics.com/)**

  AI vision software for robotic piece picking. Features PickOne perception platform with remote supervision for exception handling.



- **[Photoneo](https://www.photoneo.com/)**

  3D vision and AI for robotic bin picking. Features PhoXi 3D scanners and Bin Picking Studio for automated pick-and-place in cluttered environments.



- **[OSARO](https://www.osaro.com/)**

  AI-powered robotic picking and fulfillment automation . Combines industrial robot arms with SightWorks perception for variable products, mixed cases, and irregular packaging. AutoModel allows new SKUs without complete object model creation. Applications include mixed-case depalletizing, piece picking, kitting, and automated bagging . Deployed at Zenni Optical for eyewear order fulfillment with Cognex barcode readers .



- **[Fizyr](https://www.fizyr.com/)**

  AI-driven vision software for robotic picking (founded 2014, Delft, Netherlands) . Provides real-time object recognition and precision pick-and-place for logistics and warehousing. Key metrics: detection accuracy, SKU/parcel variety handling, and processing time for picking point generation .



- **[Mujin](https://www.mujin.co.jp/en/)**

  Intelligent robot control platform with 3D vision and motion planning for bin picking and machine tending.



- **[Knapp Pick-it-Easy](https://www.knapp.com/)**

  Robot-based piece picking system for warehouse automation with 3D vision and AI for handling diverse articles.



## Open-Source GitHub Projects



- **[GPD (Grasp Pose Detection)](https://github.com/atenpas/gpd)**

  Open-source package for detecting **6-DOF grasp poses** for 2-finger robot hands in 3D point clouds . **The foundational open-source grasp detection library.** Strengths: works for **novel objects** (no CAD models required), works in **dense clutter**, outputs **6-DOF poses** (more than just top-down grasps) . Two-step process: samples large number of grasp candidates, classifies them as viable or not . Supports single or two depth sensors with CAFFE model files . Requires PCL 1.9+, Eigen 3.0+, OpenCV 3.4+ .



- **[GraspFast](https://github.com/upc-ghy/GraspFast)**

  Multi-stage lightweight 6-DoF grasp pose fast detection for cluttered scenes (Pattern Recognition, 2025) . **Achieves ~42 FPS at highest precision** with **8.06% accuracy improvement** on "Seen" test set over SOTA . Features foreground bounding box-guided point cloud preprocessing, MinkowskiEngine-based hierarchical lightweight feature extraction, binary reliability evaluation for grasp point filtering, and optimal local sampling for multi-grasp parameter prediction . **The fastest open-source 6-DoF grasp detector available.** Deployed on Franka Emika robot for real-world cluttered scene grasping .



- **[GraphGrasp](https://github.com/BIT-robot-group/GraphGrasp)**

  Graph-guided 6-DoF grasp pose estimation network (AAAI 2026) . **Achieves nearly same performance as SOTA with ~1/5 the parameters**, significantly improving prediction speed . Graph analysis from scene, object, and grasping perspectives: graph feature embedding for scene modeling, graph transformer for object spatial relationships, multi-metric grasp pose evaluation for grasp graph construction . Outperforms previous methods in real-world robot grasping scenarios .



- **[SYN-PBOX](https://github.com/ccteaher/projects-SYN-PBOX)**

  Large-scale benchmark dataset for bin picking of box-shaped objects (Neurocomputing, 2025) . **15,000 realistic images** of 21 box-shaped objects with point clouds, RGB, depth, and detailed annotations (6D pose, segmentation mask, instance segmentation, grasping surface) . Proposes **YOLOv8-D** dual-stream network achieving **>95% grasping success rate on previously unseen real objects** after training only on synthetic data . Demonstrates effective sim-to-real transfer .



- **[FoundationPoseROS2](https://github.com/ammar-n-abbas/FoundationPoseROS2)**

  ROS2-integrated system for **6D object pose estimation and tracking** based on FoundationPose architecture . Uses RealSense2 with **Segment Anything Model 2 (SAM2)** for end-to-end, model-based, real-time pose estimation and tracking of **novel objects** . **The most modern open-source pose estimation stack for warehouse robotics.**



- **[Open Industry Project](https://github.com/Open-Industry-Project/Open-Industry-Project)**

  Free and open-source warehouse/manufacturing development framework and simulator (MIT) . **797 GitHub stars**, 107 forks, GDScript-based . **The most comprehensive open-source warehouse simulation environment** for testing robotic picking and sorting systems before deployment.



- **[Isaac Sim Logistics Sorting Robot](https://github.com/Hazzzard-LYX/Isaacsim-logistics-sorting-robot)**

  LiDAR localization, grid-map path planning, and action simulation for a logistics sorting robot in Isaac Sim (2026) . Features logistics competition field generation, real robot URDF/STL model import, **A\* path planning**, pick action, sorting baffle action, unload action, and independent 2D LiDAR known-map localization prototype . Complete task flow: pick zone identification → gripper pick → bank sorting → placement zone identification → silo unload → return to start .



- **[UR10e 3D Vision-Guided Bin Picking](https://github.com/SurabhiGupta17/UR10e-3D-Vision-Guided-Bin-Picking)**

  Autonomous bin-picking system using UR10e robotic arm with 3D vision (2025) . Integrated with Intel RealSense D435 camera for depth perception and object recognition. Software stack: ROS2 Jazzy, Gazebo Harmonic, MoveIt for motion planning, OpenCV and PCL for point cloud processing . **A complete reference implementation for UR10e-based bin picking.**



### Additional Strong Open-Source Options



- **[Robotic Grasping Papers](https://github.com/rhett-chen/Robotic-grasping-papers)** — Curated paper list of robotic grasping and related works (258 GitHub stars) . **Essential reading for understanding the field.**

- **[GraspNet Baseline](https://github.com/graspnet/graspnet-baseline)** — Baseline model for GraspNet-1Billion benchmark .

- **[Contact-GraspNet](https://github.com/NVlabs/contact_graspnet)** — PyTorch implementation of Contact-GraspNet for 6-DoF grasping .

- **[GraspNeRF](https://github.com/graspnerf/graspnerf)** — Multiview-based 6-DoF grasp detection for transparent and specular objects using NeRF (ICRA 2023) .

- Community **n8n** workflows for picking system alerting and sortation analytics automation.



**Frameworks for building custom systems**: Combine **GPD** or **GraspFast** for 6-DoF grasp detection with **GraphGrasp** for lightweight efficient inference, **FoundationPoseROS2** for novel object pose estimation, **Open Industry Project** for simulation and testing, and **Isaac Sim Logistics Sorting Robot** for path planning—creating a fully self-hosted, enterprise-grade warehouse sort system.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Warehouse robotics systems handling physical manipulation must comply with safety regulations and operational requirements.

- **Open-source grasp detection is mature but requires integration.** GPD, GraspFast, and GraphGrasp provide production-grade grasp pose detection , but deploying them on physical robots requires camera calibration, gripper integration, motion planning, and safety systems that are project-specific.

- **Sim-to-real transfer works but needs validation.** SYN-PBOX demonstrates >95% grasping success on unseen real objects after training only on synthetic data . However, performance may degrade with different object types, lighting conditions, or camera setups—validate on your specific SKUs before production deployment.

- **Grasp detection is not the same as successful picking.** A detected grasp pose may be geometrically valid but physically fail due to friction, object weight distribution, or gripper limitations. Real-world success rates depend on gripper selection, force control, and object properties.

- **GPU requirements vary.** GraspFast achieves ~42 FPS on GPU-accelerated hardware . CPU-only deployment may be significantly slower and unsuitable for high-throughput sortation lines.

- Self-hosted open-source solutions require proper security hardening, camera calibration, and ongoing maintenance. Warehouse environments are dynamic—regular recalibration and model updates are essential.



---



**Made for robotics engineers, warehouse automation specialists, and developers building transparent vision-guided sort systems.**

Let's make Computer Vision Warehouse Sort Systems more open, data-driven, and graspable.
