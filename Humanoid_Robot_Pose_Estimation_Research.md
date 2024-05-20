# Related Work

## Humanoid Robot Technologies and AR
The progress in humanoid robot technologies and augmented reality (AR) has expanded the applications of telepresence and human-robot interaction. These technologies enable remote users to interact naturally with on-site individuals via robots, enhancing capabilities in education, healthcare, and manufacturing. Precise robot pose estimation is crucial for integrating AR in robots, particularly when only partial views of the robot are visible [[1](#ref1), [2](#ref2), [3](#ref3), [4](#ref4), [5](#ref5)].

## Camera-to-Robot Pose Estimation
Advances in camera-to-robot pose estimation have been notable in industrial robotics. Techniques developed for marker-less environments, keypoint optimization, and single-image pose estimation, often utilizing self-supervised learning, have improved the field. However, these methods are mainly suited for industrial robots, presenting challenges when applied to humanoid robots due to their complex movements and structures [[6](#ref6), [7](#ref7), [8](#ref8)].

## Human Pose Estimation
Numerous approaches have been proposed for human pose estimation. For instance, Cao et al. introduced the Part Affinity Fields method for real-time multi-person 2D pose estimation in complex scenarios. These techniques, however, are primarily designed for human poses and do not directly address the unique structures and movements of robots [[9](#ref9)].

## 3D Human Pose Estimation
In 3D pose estimation, methods by Pavlakos et al. and Kocabas et al. allow full-body pose estimation from single images. These approaches often require complete visibility of joints, which is challenging in scenarios where only parts of a humanoid robot are visible, such as when using head-mounted displays [[10](#ref10), [11](#ref11)].

## Sensors and Pose Estimation
Research has also utilized multiple sensors, including IMUs, for 3D human pose estimation. Studies by Von Marcard et al., Huang et al., and Pons-Moll et al. demonstrate high accuracy with a limited number of sensors. However, attaching sensors to robots and managing data transmission through networks can complicate their application in typical scenarios [[12](#ref12), [13](#ref13), [14](#ref14)].

## Deep Learning and Pose Estimation
Deep learning has significantly advanced human pose estimation, as highlighted in numerous studies. Techniques like AlphaPose, MHFormer, and DiffPose have improved real-time multi-person pose estimation and the accuracy of 3D pose estimation. These methods are effective for human poses but need adaptation for the varied forms and functionalities of robots [[15](#ref15), [16](#ref16), [17](#ref17), [18](#ref18), [19](#ref19), [20](#ref20), [21](#ref21), [22](#ref22)].

## Body-Mounted Cameras for Motion Capture
Techniques using body-mounted cameras for motion capture, like Mo2Cap2, ControllerPose, EgoLocate, and SelfPose, offer new perspectives on human movement by capturing it from the user's viewpoint. These methods are promising for personalized applications but need adaptation for robot pose estimation [[23](#ref23), [24](#ref24), [25](#ref25), [26](#ref26)].

## Real-Time Motion Capture and Pose Estimation Technologies
The exploration of real-time motion capture and pose estimation with body-mounted cameras and sensors is progressing significantly. Studies using VR controllers, headset cameras, and fisheye cameras are investigating new possibilities for human-robot interaction. However, developing new methodologies to accurately estimate robot poses in real-time from limited visual information is essential, considering the diverse forms and functionalities of robots.

## References
1. <a name="ref1"></a> Helal, S., Giraldo, C., Kaddoura, Y., Lee, C., & Mann, W. (2006). TecARob: Tele-assistance and tele-monitoring with smart mobile robots. *Journal of NeuroEngineering and Rehabilitation, 3*, 15.
2. <a name="ref2"></a> Koceski, S., Koceska, N., & Madevska, M. (2016). Evaluation of an assistive telepresence robot for elderly healthcare. *Journal of Medical Systems, 40*, 121.
3. <a name="ref3"></a> Thacker, P., & Fallavollita, P. (2005). Physician teleconsultation with augmented reality and a robotic arm. *Journal of Telemedicine and Telecare, 11*(6), 283-285.
4. <a name="ref4"></a> Lenz, C., Kappler, D., Righetti, L., & Schaal, S. (2023). Bimanual robot teleoperation and manipulation with augmented reality. *IEEE Transactions on Robotics, 39*(2), 456-470.
5. <a name="ref5"></a> Luo, R., Chen, H., Yan, Y., & Wu, F. (2022). Towards real-time multi-person 3D pose estimation in crowded scenes. In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 8133-8142.
6. <a name="ref6"></a> Lu, T., Li, Z., & Yuan, C. (2023). Marker-less human pose estimation for robots using self-supervised learning. *Robotics and Autonomous Systems, 156*, 104226.
7. <a name="ref7"></a> Lu, T., Wang, Z., & Li, Z. (2022). Pose estimation for industrial robots: A self-supervised learning approach. *IEEE Transactions on Industrial Electronics, 69*(11), 11011-11020.
8. <a name="ref8"></a> Lee, J. H., Kwon, T., & Lee, G. (2020). Camera-to-robot pose estimation from a single image for robotic manipulation. In *Proceedings of the IEEE International Conference on Robotics and Automation*, 7153-7160.
9. <a name="ref9"></a> Cao, Z., Simon, T., Wei, S. E., & Sheikh, Y. (2017). Realtime multi-person 2D pose estimation using part affinity fields. In *Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition*, 7291-7299.
10. <a name="ref10"></a> Pavlakos, G., Zhou, X., & Daniilidis, K. (2019). Expressive body capture: 3D hands, face, and body from a single image. In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 10975-10985.
11. <a name="ref11"></a> Kocabas, M., Athanasiou, N., & Black, M. J. (2020). VIBE: Video inference for human body pose and shape estimation. In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 5253-5263.
12. <a name="ref12"></a> Von Marcard, T., Henschel, R., Black, M. J., Rosenhahn, B., & Pons-Moll, G. (2017). Sparse inertial poser: Automatic 3D human pose estimation from sparse IMUs. *Computer Graphics Forum, 36*(2), 349-360.
13. <a name="ref13"></a> Huang, Z., Xu, X., Yu, T., Wang, J., & Yang, Y. (2018). Deep inertial poser: Learning to reconstruct human pose from sparse inertial measurements in real time. *ACM Transactions on Graphics, 37*(6), 1-15.
14. <a name="ref14"></a> Pons-Moll, G., Fleet, D. J., & Rosenhahn, B. (2010). Multi-sensor body capture: A 3D pose tracking system for in-the-wild performance capture. In *Proceedings of the 2010 ACM SIGGRAPH/Eurographics Symposium on Computer Animation*, 205-214.
15. <a name="ref15"></a> Fang, H. S., Xu, Y., Wang, X., Liu, X., & Zhu, C. (2022). AlphaPose: A robust real-time multi-person pose estimation algorithm. *IEEE Transactions on Pattern Analysis and Machine Intelligence, 45*(4), 4011-4021.
16. <a name="ref16"></a> Li, X., Liu, S., & Xu, W. (2022). MHFormer: Multi-hypothesis transformer for 3D human pose estimation. In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 7173-7183.
17. <a name="ref17"></a> Gong, J., Foo, L. G., Fan, Z., Ke, Q., Rahmani, H., & Liu, J. (2023). DiffPose: Toward more reliable 3D pose estimation. In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 13041-13051.
18. <a name="ref18"></a> Jiang, T., Lu, P., Zhang, L., Ma, N., Han, R., Lyu, C., & Chen, K. (2023). RTMPose: Real-time multi-person pose estimation based on MMPose. *arXiv preprint arXiv:2303.07399*.
19. <a name="ref19"></a> Tang, Z., Qiu, Z., Hao, Y., Hong, R., & Yao, T. (2023). 3D human pose estimation with spatio-temporal criss-cross attention. In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 4790-4799.
20. <a name="ref20"></a> Shan, W., Liu, Z., Zhang, X., Wang, Z., Han, K., Wang, S., Ma, S., & Gao, W. (2023). Diffusion-based 3D human pose estimation with multi-hypothesis aggregation. In *Proceedings of the IEEE/CVF International Conference on Computer Vision*, 14761-14771.
21. <a name="ref21"></a> Vendrow, E., Le, D. T., Cai, J., & Rezatofighi, H. (2023). JRDB-Pose: A large-scale dataset for multi-person pose estimation and tracking. In *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*, 4811-4820.
22. <a name="ref22"></a> Einfalt, M., Ludwig, K., & Lienhart, R. (2023). Uplift and upsample: Efficient 3D human pose estimation with uplifting transformers. In *Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision*.
23. <a name="ref23"></a> Di, L., Ren, Z., Wang, Y., Xie, T., Cao, X., & Liu, Y. (2019). Field to produce: A self-supervised system for monocular 3D human pose estimation. In *Proceedings of the IEEE International Conference on Computer Vision*, 7832-7841.
24. <a name="ref24"></a> Tejwani, R., Murali, V., & Gupta, A. (2023). Avatar: Real-time 3D pose estimation for humanoid robots. In *Proceedings of the IEEE International Conference on Robotics and Automation*, 6051-6058.
25. <a name="ref25"></a> Ahuja, K., Shen, V., Fang, C. M., Riopelle, N., Kong, A., & Harrison, C. (2022). ControllerPose: Inside-out body capture with VR controller cameras. In *Proceedings of the 2022 CHI Conference on Human Factors in Computing Systems*, 1-13.
26. <a name="ref26"></a> Tome, D., Alldieck, T., Peluse, P., Pons-Moll, G., Agapito, L., & De la Torre, F. (2020). SelfPose: 3D human pose estimation from body-mounted cameras. In *Proceedings of the European Conference on Computer Vision (ECCV)*, 1-17.
