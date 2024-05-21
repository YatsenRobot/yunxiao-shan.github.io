---
title: "SiamFPN: A Deep Learning Method for Accurate and Real-Time Maritime Ship Tracking"
collection: publications
permalink: /publication/2024-02-17-paper-title-number-4
date: 2021-01-01
venue: 'IEEE Transactions on Circuits and Systems for Video Technology'
paperurl: 'https://ieeexplore.ieee.org/document/9024119'
citation: '@article{shan2020siamfpn,
  title={SiamFPN: A deep learning method for accurate and real-time maritime ship tracking},
  author={Shan, Yunxiao and Zhou, Xiaomei and Liu, Shanghua and Zhang, Yunfei and Huang, Kai},
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  volume={31},
  number={1},
  pages={315--325},
  year={2020},
  publisher={IEEE}
}'
---

Visual object tracking plays an essential role in various maritime applications. However, most of the existing tracking methods belong to generative models, which only focus on the features of the object and require the target has significant visual saliency for accurate tracking. While the visual saliency is available in most of the common tracking conditions, these methods may fail when facing challenging situations. In this paper, a deep learning based tracking method is proposed to track maritime ships, namely, SiamFPN. In SiamFPN, a modified Siamese Network is combined with multi-RPNs to build a tracking pipeline. Concretely, A ResNet-50 with an FPN structure is used as the CNN of the detection subnetwork of Siamese, and a template subnetwork is parallel to the detection. In order to strengthen the discriminative ability, three RPNs are deployed to process the output of Siamese Network. Moreover, a historical impacts based proposal selection method is developed for selecting correct target areas. Finally, a dataset is collected for training and testing SiamFPN and validating our excellent performance over the other four recent SOTA trackers. Based on the experimental results, we achieved 74 % on average accuracy with real-time speed.
