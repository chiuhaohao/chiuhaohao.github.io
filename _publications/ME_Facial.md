---
title: "Fair Multi-Exit Framework for Facial Attribute Classification"
collection: publications
permalink: 
excerpt: ''
date: 2023/02/01
venue: 'AAAI 2023 Workshop on Artificial Intelligence for Social Good'
paperurl: 'https://arxiv.org/abs/2301.02989'
citation: 'Chiu, Ching-Hao, et al. "Fair Multi-Exit Framework for Facial Attribute Classification." arXiv preprint arXiv:2301.02989 (2023).'
---

![Method](https://user-images.githubusercontent.com/43490777/203788375-ea59d791-942f-4d42-87df-26a9f577b381.png)

Fairness has become increasingly pivotal in facial recognition. Without bias mitigation, deploying unfair AI would harm the interest of the underprivileged population. In this paper, we observe that though the higher accuracy that features from the deeper layer of a neural networks generally offer, fairness conditions deteriorate as we extract features from deeper layers. This phenomenon motivates us to extend the concept of multi-exit framework. Unlike existing works mainly focusing on accuracy, our multi-exit framework is fairness-oriented, where the internal classifiers are trained to be more accurate and fairer. During inference, any instance with high confidence from an internal classifier is allowed to exit early. Moreover, our framework can be applied to most existing fairness-aware frameworks. Experiment results show that the proposed framework can largely improve the fairness condition over the state-of-the-art in CelebA and UTK Face datasets.
