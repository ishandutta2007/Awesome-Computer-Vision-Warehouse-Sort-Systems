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

- **[FoundationPose](https://github.com/NVlabs/FoundationPose)** [![GitHub stars](https://img.shields.io/github/stars/NVlabs/FoundationPose?style=social&color=white)](https://github.com/NVlabs/FoundationPose/stargazers)
  Unified 6D pose estimation and tracking framework for novel and arbitrary objects from NVIDIA. Eliminates CAD model requirements at test time, providing high-precision, real-time tracking for complex warehouse picking cells.

- **[PyRender](https://github.com/mmatl/pyrender)** [![GitHub stars](https://img.shields.io/github/stars/mmatl/pyrender?style=social&color=white)](https://github.com/mmatl/pyrender/stargazers)
  Fast, lightweight, GPU-accelerated Python library for physically-based rendering and visualization of 3D scenes, widely used to synthesize depth and RGB-D scenes for bin-picking models.

- **[GraspNet Baseline](https://github.com/graspnet/graspnet-baseline)** [![GitHub stars](https://img.shields.io/github/stars/graspnet/graspnet-baseline?style=social&color=white)](https://github.com/graspnet/graspnet-baseline/stargazers)
  Official baseline models and benchmark evaluation tools for the GraspNet-1Billion dataset. Standard toolset for 6-DoF robotic grasp pose generation in cluttered warehouse and tabletop environments.

- **[AnyGrasp SDK](https://github.com/graspnet/anygrasp_sdk)** [![GitHub stars](https://img.shields.io/github/stars/graspnet/anygrasp_sdk?style=social&color=white)](https://github.com/graspnet/anygrasp_sdk/stargazers)
  General object robotic grasping toolkit based on large-scale grasp models. Supports rapid 6-DoF gripper pose evaluation across arbitrary unknown geometries and dense piles in logistics setups.

- **[Open Industry Project](https://github.com/Open-Industry-Project/Open-Industry-Project-Godot)** [![GitHub stars](https://img.shields.io/github/stars/Open-Industry-Project/Open-Industry-Project-Godot?style=social&color=white)](https://github.com/Open-Industry-Project/Open-Industry-Project-Godot/stargazers)
  Open-source warehouse and factory automation simulator built on Godot Engine. Features full PLC industrial protocol communications (OPC UA, Modbus, Siemens S7, EtherNet/IP, UR RTDE) to simulate sorting conveyors and robotic cells.

- **[GPD (Grasp Pose Detection)](https://github.com/atenpas/gpd)** [![GitHub stars](https://img.shields.io/github/stars/atenpas/gpd?style=social&color=white)](https://github.com/atenpas/gpd/stargazers)
  Foundational open-source package for detecting 6-DoF grasp poses for 2-finger robot hands in 3D point clouds without CAD models, designed specifically to operate inside dense bin clutter.

- **[Robotic Grasping (GG-CNN)](https://github.com/skumra/robotic-grasping)** [![GitHub stars](https://img.shields.io/github/stars/skumra/robotic-grasping?style=social&color=white)](https://github.com/skumra/robotic-grasping/stargazers)
  Generative Grasping Convolutional Neural Network (GG-CNN) predicting pixel-wise antipodal grasp quality, angle, and width from depth images in real time (~50 Hz) for closed-loop dynamic sorting.

- **[Contact-GraspNet](https://github.com/NVlabs/contact_graspnet)** [![GitHub stars](https://img.shields.io/github/stars/NVlabs/contact_graspnet?style=social&color=white)](https://github.com/NVlabs/contact_graspnet/stargazers)
  NVIDIA PyTorch implementation of Contact-GraspNet for end-to-end 6-DoF grasp generation from single or multi-view point clouds based on grasp contact point probability.

- **[Robotic Grasping Papers](https://github.com/rhett-chen/Robotic-grasping-papers)** [![GitHub stars](https://img.shields.io/github/stars/rhett-chen/Robotic-grasping-papers?style=social&color=white)](https://github.com/rhett-chen/Robotic-grasping-papers/stargazers)
  Curated taxonomy and literature collection on robotic grasping, 6-DoF pose detection, tactile sensing, and reinforcement learning for warehouse manipulation.

- **[Dex-Net](https://github.com/BerkeleyAutomation/dex-net)** [![GitHub stars](https://img.shields.io/github/stars/BerkeleyAutomation/dex-net?style=social&color=white)](https://github.com/BerkeleyAutomation/dex-net/stargazers)
  UC Berkeley's Dexterity Network codebase for generating massive synthetic grasp datasets, computing 3D analytic grasp metrics, and training robust grasp quality convolutional networks (GQ-CNN).

- **[GQ-CNN (Grasp Quality CNN)](https://github.com/BerkeleyAutomation/gqcnn)** [![GitHub stars](https://img.shields.io/github/stars/BerkeleyAutomation/gqcnn?style=social&color=white)](https://github.com/BerkeleyAutomation/gqcnn/stargazers)
  Package for training and deploying Grasp Quality Convolutional Neural Networks on depth images for parallel-jaw grippers and suction cups in high-throughput bin-picking.

- **[FoundationPoseROS2](https://github.com/ammar-n-abbas/FoundationPoseROS2)** [![GitHub stars](https://img.shields.io/github/stars/ammar-n-abbas/FoundationPoseROS2?style=social&color=white)](https://github.com/ammar-n-abbas/FoundationPoseROS2/stargazers)
  ROS2 production-ready integration combining Segment Anything 2 (SAM2) and FoundationPose for real-time 6D object pose tracking with Intel RealSense cameras in sorting cells.

- **[GraspNeRF](https://github.com/PKU-EPIC/GraspNeRF)** [![GitHub stars](https://img.shields.io/github/stars/PKU-EPIC/GraspNeRF?style=social&color=white)](https://github.com/PKU-EPIC/GraspNeRF/stargazers)
  Multiview-based 6-DoF grasp detection using generalizable Neural Radiance Fields (NeRF), resolving grasp prediction for challenging transparent and specular items where standard depth sensors fail (ICRA 2023).

- **[SceneNet](https://github.com/ankurhanda/SceneNet)** [![GitHub stars](https://img.shields.io/github/stars/ankurhanda/SceneNet?style=social&color=white)](https://github.com/ankurhanda/SceneNet/stargazers)
  Repository and tools for generating photo-realistic synthetic indoor scenes, trajectory data, and depth maps used in training robotic perception and cluttered bin understanding algorithms.

- **[SYN-PBOX](https://github.com/ccteaher/projects-SYN-PBOX)** [![GitHub stars](https://img.shields.io/github/stars/ccteaher/projects-SYN-PBOX?style=social&color=white)](https://github.com/ccteaher/projects-SYN-PBOX/stargazers)
  Benchmark dataset and YOLOv8-D dual-stream vision network for robotic bin-picking of box-shaped objects (15,000 synthetic annotated images achieving >95% zero-shot real picking transfer).

- **[UR10e 3D Vision-Guided Bin Picking](https://github.com/SurabhiGupta17/UR10e-3D-Vision-Guided-Bin-Picking)** [![GitHub stars](https://img.shields.io/github/stars/SurabhiGupta17/UR10e-3D-Vision-Guided-Bin-Picking?style=social&color=white)](https://github.com/SurabhiGupta17/UR10e-3D-Vision-Guided-Bin-Picking/stargazers)
  Autonomous bin-picking reference stack for Universal Robots UR10e using ROS2 Jazzy, Gazebo Harmonic, MoveIt motion planning, and RealSense D435 camera point clouds.

- **[Isaac Sim Logistics Sorting Robot](https://github.com/Hazzzard-LYX/Isaacsim-logistics-sorting-robot)** [![GitHub stars](https://img.shields.io/github/stars/Hazzzard-LYX/Isaacsim-logistics-sorting-robot?style=social&color=white)](https://github.com/Hazzzard-LYX/Isaacsim-logistics-sorting-robot/stargazers)
  End-to-end simulation environment in NVIDIA Isaac Sim for logistics sorting: LiDAR localization, A* path navigation, pick-action, bank sortation, and container offloading.

- **[GraphGrasp](https://github.com/BIT-robot-group/GraphGrasp)** [![GitHub stars](https://img.shields.io/github/stars/BIT-robot-group/GraphGrasp?style=social&color=white)](https://github.com/BIT-robot-group/GraphGrasp/stargazers)
  Graph-guided 6-DoF grasp pose estimation network (AAAI 2026) achieving SOTA accuracy with ~1/5 the model parameters via hierarchical graph transformers modeling spatial relationships.

- **[GraspFast](https://github.com/upc-ghy/Franka-GraspFast)** [![GitHub stars](https://img.shields.io/github/stars/upc-ghy/Franka-GraspFast?style=social&color=white)](https://github.com/upc-ghy/Franka-GraspFast/stargazers)
  Multi-stage lightweight 6-DoF grasp pose detector running at ~42 FPS on GPU for cluttered bins, deployed on Franka Emika robotic arms (Pattern Recognition, 2025).

**Frameworks for building custom systems**: Combine **FoundationPose** or **FoundationPoseROS2** for novel object pose tracking, **GPD**, **Contact-GraspNet**, or **GraspFast** for 6-DoF grasp detection, **GraphGrasp** for lightweight inference, **Open Industry Project** or **Isaac Sim** for simulation, and **GQ-CNN** for grasp verification—creating a fully self-hosted, enterprise-grade warehouse sortation system.

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
