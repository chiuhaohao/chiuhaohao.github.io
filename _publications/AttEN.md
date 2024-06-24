---
title: "Achieve Fairness without Demographics for Dermatological Disease Diagnosis"
collection: publications
permalink: 
excerpt: ''
date: 2024/07/01
venue: 'Medical Image Analysis'
slidesurl: 
paperurl: 'https://www.sciencedirect.com/science/article/pii/S1361841524001130?via%3Dihub'
citation: 'Chiu, Ching-Hao, et al. "Achieve Fairness without Demographics for Dermatological Disease Diagnosis." arXiv preprint arXiv:2401.08066 (2024).'
---
<img width="796" alt="截圖 2024-06-24 下午2 54 38" src="https://github.com/chiuhaohao/chiuhaohao.github.io/assets/53943319/2ffaaebc-8619-46a4-926d-c5b8b2dcc6c7">


In medical image diagnosis, fairness has become increasingly crucial. Without bias mitigation, deploying unfair AI would harm the interests of the underprivileged population and potentially tear society apart. Recent research addresses prediction biases in deep learning models concerning demographic groups (e.g., gender, age, and race) by utilizing demographic (sensitive attribute) information during training. However, many sensitive attributes naturally exist in dermatological disease images. If the trained model only targets fairness for a specific attribute, it remains unfair for other attributes. Moreover, training a model that can accommodate multiple sensitive attributes is impractical due to privacy concerns. To overcome this, we propose a method enabling fair predictions for sensitive attributes during the testing phase without using such information during training. Inspired by prior work highlighting the impact of feature entanglement on fairness, we enhance the model features by capturing the features related to the sensitive and target attributes and regularizing the feature entanglement between corresponding classes. This ensures that the model can only classify based on the features related to the target attribute without relying on features associated with sensitive attributes, thereby improving fairness and accuracy. Additionally, we use disease masks from the Segment Anything Model (SAM) to enhance the quality of the learned feature. Experimental results demonstrate that the proposed method can improve fairness in classification compared to state-of-the-art methods in two dermatological disease datasets.
