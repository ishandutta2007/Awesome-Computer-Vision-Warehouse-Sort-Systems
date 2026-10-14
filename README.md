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

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global warehouse robotics market is estimated at **$7.7B to $10.0B** in 2025–2026, advancing at a **~14–17% CAGR** under escalating supply-chain throughput demands and fulfillment labor constraints. Market dynamics exhibit a **dual-tier structure**: foundational intralogistics infrastructure remains concentrated among established industrial conglomerates (e.g., KNAPP, Daifuku, Dematic), whereas the AI vision, autonomous mobile manipulator, and 6-DoF picking layer is **moderately fragmented** with innovative pure-play startups and RaaS providers competing intensely across specialized perception and manipulation niches.

## SaaS/Hosted Platforms

| Platform | Company Valuation / Revenue | Starting Pricing Tier | Free Tier Limits | Key Capabilities & Overview |
| :--- | :--- | :--- | :--- | :--- |
| **[KNAPP Pick-it-Easy](https://www.knapp.com/)** | **€2.14B (~$2.33B)** annual revenue (FY 2025/26) | Starting at **~$8,500/month/cell** (RaaS lease & software support contract) | **30-day guided pilot evaluation** (limited to 1 simulated workstation and benchmark SKU dataset) | Robot-based piece picking workstation for warehouse logistics with AI-guided 3D vision, auto-handling diverse retail and pharma articles. |
| **[Dexterity](https://www.dexterity.ai/)** | **$1.65B** valuation ($380M+ raised; ~$66M ARR) | Starting at **~$6,000/month/robot** (RaaS model, base tier palletizing & singulation) | **30-day proof-of-concept trial** (limited to 1 physical cell test or synthetic environment digital twin simulation) | Full-stack robotic picking and mobile manipulation with dual-arm tactile sensing for unstructured environments like truck unloading and singulation. |
| **[Mujin](https://www.mujin.co.jp/en/)** | **$1.0B+** valuation ($150M+ raised; ~$116M revenue) | Starting at **~$4,500/month/controller** (Mujin Controller 3D vision & motion planning license) | **14-day simulation sandbox trial** (virtual digital twin picking environment limited to 5 test CAD models) | Real-time motion planning and 3D perception platform powering autonomous bin picking, machine tending, and depalletizing. |
| **[Covariant](https://covariant.ai/)** | **$625M** valuation ($245M raised; tech licensed by Amazon) | Starting at **~$3,500/month/station** (Covariant Brain vision software license tier) | **30-day enterprise evaluation** (benchmarked against client dataset of up to 500 SKU scans) | Universal AI robotic brain (RFM-1) for piece picking, order induction, and mixed-case sortation across varied and irregular SKUs. |
| **[Berkshire Grey](https://www.berkshiregrey.com/)** | **$375M** valuation (SoftBank acquisition; ~$51M revenue) | Starting at **~$7,500/month/system** (Robotics-as-a-Service base sortation & picking module) | **30-day operational feasibility trial** (evaluation limited to sample parcel profile analysis and warehouse workflow assessment) | Intelligent enterprise robotics for fulfillment; features AI-powered piece picking, robotic induction, and parcel sortation. |
| **[OSARO](https://www.osaro.com/)** | **~$175M** valuation ($95M raised; ~$15M ARR) | Starting at **~$2,500/month/robot** (SightWorks AI vision software license) | **30-day software pilot license** (limited to single-camera 2D/3D feed and 1,000 simulated pick cycles) | Hardware-agnostic AI perception and piece-picking software for automated bag kitting, induction, and mixed-case depalletizing. |
| **[Ambi Robotics](https://ambirobotics.com/)** | **~$150M** valuation ($67M raised; ~$12M ARR) | Starting at **~$3,000/month/cell** (AmbiSort software & system operational subscription) | **14-day warehouse throughput trial** (limited to pre-deployment simulation run on up to 250 sample packages) | AI-powered robotic sorting systems (AmbiSort) leveraging Sim2Real deep learning and suction manipulation for parcel handling. |
| **[Plus One Robotics](https://plusonerobotics.com/)** | **~$140M** valuation ($100M raised; ~$18M ARR) | Starting at **~$2,200/month/arm** (PickOne AI vision software subscription) | **30-day supervised pilot trial** (includes up to 50 hours of Yonder human-in-the-loop exception handling assistance) | 3D perception AI software for piece picking and parcel induction with Yonder cloud-based human-in-the-loop remote supervision. |
| **[Photoneo](https://www.photoneo.com/)** | **~$90M** valuation (Acquired by Zebra Technologies; ~$35M rev) | Starting at **~$490/month** (Bin Picking Studio vision & localization software license; scanner purchased separately) | **30-day fully functional trial license** (Bin Picking Studio complete features, limited to 1 workstation/dongle) | 3D vision and localization software paired with PhoXi 3D scanners and MotionCam-3D for bin-picking in cluttered environments. |
| **[Fizyr](https://www.fizyr.com/)** | **~$35M** valuation ($4M+ seed raised; ~$9M revenue) | Starting at **~$1,800/month/pick-point** (Fizyr OS deep learning vision software license) | **30-day developer evaluation trial** (limited to offline dataset inference on up to 2,000 images/point clouds) | Plug-and-play deep learning vision software for system integrators, providing real-time 6-DoF picking poses for unknown parcels and SKUs. |



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
