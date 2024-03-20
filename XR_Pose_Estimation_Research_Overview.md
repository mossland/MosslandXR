# Extended Reality Research on Pose Estimation

## Introduction

This document reviews significant contributions in the field of Extended Reality (XR), focusing on pose estimation technologies that enable the creation of virtual avatars mirroring real-world human movements. Pose estimation plays a crucial role in bridging the gap between virtual and physical realms, facilitating immersive and interactive experiences in virtual reality (VR), augmented reality (AR), and mixed reality (MR) environments.

## Paper Reviews

### Realtime Multi-Person 2D Pose Estimation Using Part Affinity Fields (CVPR 2018)

This foundational paper introduces a method for real-time 2D pose estimation for multiple people within a scene. The technique, based on Part Affinity Fields (PAFs), offers a novel approach to identify and associate body parts with individual persons in complex scenes, paving the way for more interactive and engaging virtual environments.

- [Read more](https://openaccess.thecvf.com/content_cvpr_2017/html/Cao_Realtime_Multi-Person_2D_CVPR_2017_paper.html)

### SMPL: A Skinned Multi-Person Linear Model (TOG 2015)

The SMPL model introduces a versatile, skinnable, and deformable mesh that can accurately represent a wide range of human body shapes and poses using a relatively low number of parameters. This advancement is crucial for generating realistic human avatars in VR applications, allowing for personalized avatar creation based on the user's specific body metrics.

- [Read more](https://dl.acm.org/doi/abs/10.1145/3596711.3596800)

### Keep It SMPL: Automatic Estimation of 3D Human Pose and Shape from a Single Image (ECCV 2016)

Explores the integration of the SMPL model with single-image input to estimate 3D human pose and shape, making it more accessible for applications that have limited data input capabilities.

- [Read more](https://link.springer.com/chapter/10.1007/978-3-319-46454-1_34)

### Expressive Body Capture: 3D Hands, Face, and Body From a Single Image (CVPR 2019)

This work demonstrates capturing detailed 3D models of the human body, including nuanced expressions of the face and hands, from a single image. Such technology enhances the realism and expressiveness of avatars in virtual environments, enabling more nuanced and personal interactions.

- [Read more](https://openaccess.thecvf.com/content_CVPR_2019/html/Pavlakos_Expressive_Body_Capture_3D_Hands_Face_and_Body_From_a_CVPR_2019_paper.html)

### LiveCap: Real-Time Human Performance Capture From Monocular Video (SIGGRAPH 2019)

Introduces a technique for live human performance capture using a single monocular video, pushing forward the capabilities for real-time and on-the-go 3D motion capture without the need for complex setups.

- [Read more](https://dl.acm.org/doi/abs/10.1145/3311970)

### Mo2Cap2: Real-time Mobile 3D Motion Capture with a Cap-mounted Fisheye Camera (IEEE VR 2019)

Presents a novel approach for real-time 3D motion capture using a single fisheye camera mounted on a cap, enabling more flexible and mobile capture solutions for VR applications.

- [Read more](https://ieeexplore.ieee.org/abstract/document/8643070)

### PhysCap: Physically Plausible Monocular 3D Motion Capture in Real Time (SIGGRAPH Asia 2020)

Explores real-time 3D motion capture from a single monocular video feed while ensuring physical plausibility in the captured movements, a key advancement for creating realistic virtual interactions.

- [Read more](https://dl.acm.org/doi/abs/10.1145/3414685.3417877)

### QuestSim: Human Motion Tracking from Sparse Sensors with Simulated Avatars (SIGGRAPH Asia 2022)

Explores human motion tracking using sparse sensors and simulated avatars, presenting a significant advancement in creating realistic virtual representations of human movements.

- [Meta AI Research: Quest 2 Body Pose Estimation Without Trackers](https://www.uploadvr.com/meta-quest-2-body-tracking-without-trackers/)
- [YouTube - Meta Research: Quest 2 Body Tracking Without Extra Trackers](https://www.youtube.com/watch?v=QI4aMf-244A)
- [YouTube - QuestSim: Human Motion Tracking from Sparse Sensors with Simulated Avatars](https://www.youtube.com/watch?v=CkTHsz6Ldas)

### QuestEnvSim: Environment-Aware Simulated Motion Tracking from Sparse Sensors (SIGGRAPH 2023)

Introduces environment-aware simulated motion tracking leveraging sparse sensors, enhancing the interaction between virtual avatars and their surroundings.

- [Read more](https://arxiv.org/abs/2306.05666)
- [YouTube - QuestEnvSim](https://www.youtube.com/watch?v=HXkp3ILm5bY)

### Controllerpose: Inside-out Body Capture with VR Controller Cameras (CHI 2022)

Presents an innovative method for body capture using VR controller cameras, offering new possibilities for interactive VR experiences.

- [Read more](https://dl.acm.org/doi/abs/10.1145/3491102.3502105)

### Deepmimic: Example-guided Deep Reinforcement Learning of Physics-based Character Skills (SIGGRAPH 2018)

Showcases the use of example-guided deep reinforcement learning to teach virtual characters physics-based skills, pushing the boundaries of character animation in virtual environments.

- [Read more](https://dl.acm.org/doi/abs/10.1145/3197517.3201311)

### Physics-based Motion Capture Imitation with Deep Reinforcement Learning (SIGGRAPH 2018)

Explores the imitation of physics-based motion capture using deep reinforcement learning, enhancing the realism of virtual character movements.

- [Read more](https://dl.acm.org/doi/abs/10.1145/3274247.3274506)

### Fusing Monocular Images and Sparse IMU Signals for Real-time Human Motion Capture (SIGGRAPH Asia 2023)

Introduces a method for real-time human motion capture by fusing monocular images and sparse IMU signals, contributing to advancements in motion capture technology.

- [Read more](https://arxiv.org/abs/2309.00310)


### EgoLocate: Real-time Motion Capture, Localization, and Mapping with Sparse Body-mounted Sensors (SIGGRAPH 2023)

EgoLocate introduces an innovative approach to motion capture using minimal sensors attached to the body. This technique allows for accurate tracking and mapping of human movements in real-time, ideal for on-the-go AR experiences and applications in navigation and sports training.

- [Read more](https://arxiv.org/abs/2305.01599)

### Real-time Pose Estimation from Images for Multiple Humanoid Robots (RoboCup International Symposium 2021)

This paper proposes a lightweight model designed for 2D pose estimation of multiple humanoid robots, addressing the challenge in real-time environments such as the RoboCup Humanoid League. A novel dataset, the HumanoidRobotPose dataset, is introduced to support this effort, demonstrating potential advancements for soccer-playing robots.

- [Read more](https://arxiv.org/abs/2107.02675)

### An Avatar Robot Overlaid with the 3D Human Model of a Remote Operator (IROS 2023)

Introduces an Avatar Robot System, a mixed real/virtual robotic system that physically interacts with a person while being overlaid with the 3D model of a remote operator through Augmented Reality (AR). This approach enhances the sense of presence and trust in telepresence assistive robots.

- [Read more](https://arxiv.org/pdf/2303.02546.pdf)

### VIBE: Video Inference for Human Body Pose and Shape Estimation (CVPR 2020)

VIBE is a video-based model that estimates human pose and shape from video sequences using a combination of a motion discriminator and a pose and shape regression network. This method significantly improves the accuracy and realism of pose estimation over image-based methods.

- [Read more](file-fvXAKaqO6m8gk79cqc6rl5TB)

### Back to Optimization: A New Approach to Real-time Multi-person 2D Pose Estimation (WACV 2024)

Presents a novel optimization-based approach for real-time multi-person 2D pose estimation, focusing on achieving high accuracy and efficiency. This method revisits traditional optimization techniques with modern deep learning insights to improve pose estimation performance.

- [Read more](file-wrtNmvVvsxAisQWGKyHVtAGi)

## Code Reviews

### OpenPose

OpenPose represents a breakthrough in body, face, and hand estimation, providing an open-source framework that has been instrumental in advancing research and applications in human pose estimation. It enables the detection of human figures in images and video, crucial for interactive VR/AR applications.

- [GitHub Repository](https://github.com/CMU-Perceptual-Computing-Lab/openpose)

### Pytorch Stacked Hourglass

This implementation of the Stacked Hourglass Network in PyTorch facilitates accurate and efficient pose estimation. The model's design allows for repeated bottom-up, top-down processing, enhancing the precision of pose detection across scales, vital for detailed avatar animation.

- [GitHub Repository](https://github.com/bearpaw/pytorch-pose)

### DeepMimic

DeepMimic showcases how deep reinforcement learning can be used to teach virtual characters to perform complex physical tasks in a realistic manner. This approach opens new avenues for creating more lifelike and autonomously learning avatars in XR environments.

- [GitHub Repository](https://github.com/xbpeng/DeepMimic)

## Conclusion

The exploration of pose estimation in XR environments reveals a rapidly evolving field at the intersection of computer vision, machine learning, and interactive technologies. The advancements discussed herein not only push the boundaries of what's possible in virtual reality applications but also offer new opportunities for enhancing physical-virtual interactions, creating more immersive, realistic, and personalized experiences in XR.
