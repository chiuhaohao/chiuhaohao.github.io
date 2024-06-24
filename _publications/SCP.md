---
title: "Achieving Fairness Through Channel Pruning for Dermatological Disease Diagnosis"
collection: publications
permalink: 
excerpt: ''
date: 2024/10/01
venue: 'International Conference on Medical Image Computing and Computer Assisted Intervention 2024'
slidesurl: ''
paperurl: 'https://arxiv.org/abs/2405.08681'
citation: 'Kong, Qingpeng, et al. "Achieving Fairness Through Channel Pruning for Dermatological Disease Diagnosis." arXiv preprint arXiv:2405.08681 (2024).'
---

<img width="1133" alt="截圖 2024-06-24 下午2 56 04" src="https://github.com/chiuhaohao/chiuhaohao.github.io/assets/53943319/089c3c22-f1e4-4778-a6c7-f17413d3d394">


Numerous studies have revealed that deep learning-based medical image classification models may exhibit bias towards specific demographic attributes, such as race, gender, and age. Existing bias mitigation methods often achieve high level of fairness at the cost of significant accuracy degradation. In response to this challenge, we propose an innovative and adaptable Soft Nearest Neighbor Loss-based channel pruning framework, which achieves fairness through channel pruning. Traditionally, channel pruning is utilized to accelerate neural network inference. However, our work demonstrates that pruning can also be a potent tool for achieving fairness. Our key insight is that different channels in a layer contribute differently to the accuracy of different groups. By selectively pruning critical channels that lead to the accuracy difference between the privileged and unprivileged groups, we can effectively improve fairness without sacrificing accuracy significantly. Experiments conducted on two skin lesion diagnosis datasets across multiple sensitive attributes validate the effectiveness of our method in achieving state-of-the-art trade-off between accuracy and fairness. Our code is available at https://github.com/Kqp1227/Sensitive-Channel-Pruning.
