---
title: "Robust Cooperative Localization with Failed Communication and Biased Measurements"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper introduces a cl method to accurately locate robots under challenging scenarios.'
date:2024.01
venue: 'IEEE Robotics and Automation Letters'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
citation: '
@ARTICLE{10423111,
  author={He, Ronghai and Shan, Yunxiao and Huang, Kai},
  journal={IEEE Robotics and Automation Letters}, 
  title={Robust Cooperative Localization With Failed Communication and Biased Measurements}, 
  year={2024},
  volume={9},
  number={3},
  pages={2997-3004}
  }
'
---

Cooperative Localization (CL) plays a crucial role in achieving precise localization without relying on localization sensors. However, the performance of CL can be significantly affected by failed communication and biased measurements. This letter presents a robust decentralized CL method that addresses these challenges effectively. To tackle the issue of communication failures, the proposed method adopts a multi-centralized framework that separates the measurement and communication processes. This decoupling allows each robot to utilize measurement information even in the absence of communication. Additionally, an reasonable state estimation method for other robots is proposed by approximating the actual input velocity model of unknown states and then propagating them using the motion model. To handle biased measurements, the method incorporates the M-estimation technique into the measurement update process. This technique weights the received measurements according to their reliability, mitigating the impact of biased measurements on the estimation accuracy. Simulation experiments have been conducted to validate the effectiveness of the proposed method in challenging scenarios.
