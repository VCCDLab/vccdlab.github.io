---
layout: page
title: Temporal Action Dection
description: Open-set Temporal Action Dection in the Wild.
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---
Open-set Temporal Action Localization (OSTAL) is a critical and challenging task that aims to recognize and temporally localize human actions in untrimmed videos in open word scenarios. The main challenge in this task is the knowledge transfer from known actions to unknown actions. However, existing methods utilize limited training data and overparameterized deep neural network, which have poor generalization. This paper proposes a novel Generalized OSTAL model (namely GOTAL) to learn generalized representations of actions. GOTAL utilizes a Transformer network to model actions and a open-set detection head to perform action localization and recognition. Benefitting from Transformer’s temporal modeling capabilities, GOTAL facilitates the extraction of human motion information from videos to mitigate the effects of irrelevant background data. Furthermore, a sharpness minimization algorithm is used to learn the network parameters of GOTAL, which facilitates the convergence of network parameters towards flatter minima by simultaneously minimizing the training loss value
and sharpness of the loss plane. The collaboration of the above components significantly enhances the generalization of the representation. Experimental results demonstrate that GOTAL achieves the state-of-the-art performance on THUMOS14 and ActivityNet1.3 benchmarks, confirming the effectiveness of our proposed method. 
