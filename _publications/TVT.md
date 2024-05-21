---
title: "A Reinforcement Learning-Based Adaptive Path Tracking Approach for Autonomous Driving"
collection: publications
permalink: /publication/TVT
excerpt: ' IEEE Transactions on Vehicular Technology'
date: 2020-10-28
venue: 'IEEE Transactions on Vehicular Technology'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9161291'
citation: '@article{shan2020reinforcement,
  title={A reinforcement learning-based adaptive path tracking approach for autonomous driving},
  author={Shan, Yunxiao and Zheng, Boli and Chen, Longsheng and Chen, Long and Chen, De},
  journal={IEEE Transactions on Vehicular Technology},
  volume={69},
  number={10},
  pages={10581--10595},
  year={2020},
  publisher={IEEE}
}
  '
---
The path tracking system is a crucial component in fully autonomous vehicles. While many methods provide stateof-the-art tracking performance, they tend to emphasize tracking accuracy for safety, at the price of ride quality. Although methods based on a dynamic model and optimization theory guarantee improved tracking performance, a high-fidelity model is unavailable in most autonomous systems, and the complex optimization process may increase the computational burden. Therefore, for practical, real-life systems, it is urgent to develop a tracking method with a simple, effective control framework for real-time implementation. Moreover, the tracking approach should adaptively balance between tracking accuracy and the passenger experience. With that in mind, a simple tracking scheme with adaptive lateral and longitudinal control approaches is proposed. For lateral control, a pure pursuit (PP) geometric controller is used as a basic tracking framework to design the steering method. A detailed analysis shows that PP inefficiently reduces the lateral error. A PID controller is integrated with PP by a customized reinforcement learning model to better deal with tracking error by trading off between PP and PID. Moreover, a rough-to-fine velocity adaptation method is proposed to adjust the speed according to the geometry of the predefined path and the real-time tracking feedback. The proposed controlling approach is tested in different path tracking scenarios. The results show that the approach can adaptively change the weights of PP and PID to maintain a balance between tracking error (within ±0.5 m) and jerk (within ±0.5 m/s 3 ),and can adapt to high-speed scenarios (up to 80 km/h). Finally, a field test is carried out to validate the practicability.