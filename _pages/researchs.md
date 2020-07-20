---
<!-- layout: archive -->
title: "Research Experiences"
permalink: /researchs/
author_profile: true
---

Academic Visiting at Department of Computer Science, University of Science and Technology of China
======
* Key Laboratory of advanced simulation technology aviation science and technology, Beijing, CN, SEP./2018-PRESENT
* Advisor: Prof. Shangfei Wang and Prof. Enhong Chen
* During this time, I concentrated on micro-expression recognition problem. Micro-expressions are subtle and brief facial expression thus very hard to recognize. Past works have already used various handcrafted features and deep features in this problem but resulted in poor performances. We adopted an adversarial learning framework that leveraged normal facial expression images, named macro-expressions, to assist the recognition of micro-expressions. We believed that micro-expression and macro-expression with same expression labels could have similar features by proper feature extractor after adversarial learning. Our proposed method outperformed all state-of-the-art method in CAMSE2, SMIC databases and in the composite database task.
* Achievements: Learning from Macro-expression: an Adversarial Micro-expression RecognitionFramework. [[PDF]](http://Wei-kang-Wang.github.io/files/Micro-expression.pdf)

Internship in Institute of Automation, Chinese Academy of Science
======
* [Center for Biometrics and Security Research (CBSR), National Laboratory of Pattern Recognition of China](http://www.cbsr.ia.ac.cn/english/index.asp), Beijing, CN, SEP./2016-NOV./2016
* Advisor: Dr. Stan Li.
* I merged Megaface database, MS-Celeb-1M database and CASIA database into one database with images of a same identity merged. This was completed by first adopting a CNN to extract features and then evaluated the similarity matrix of every two features. Pairs with low similarity value below a threshold will be assumed not the same and with high accuracy need to be checked manually. But by adjusting the threshold we can find a balance between the fusion accuracy and the time we need to take and the key is actually how well the features got from the CNN.
  
Research Project: A New VC Dimension Based on Probability[[PDF]](http://dpi-proceedings.com/index.php/dtcse/article/viewFile/8239/7812)
======
* School of Automation Science and Electrical Engineering, Beihang University, Beijing, CN, MAR./2016-Jun./2016
* Advisor: Prof. B. Zhang
* We considered a new variant of VC dimension by leveraging information from data distribution. Original VC dimension gave a measure of learning ability based on all possible training data distributions, while in many real situations, we only need to concentrate on limited ones. Thus we proposed a new VC dimension which took data distributions into consideration and we proved that the original VC bound was also applicable in our new definition. Thus if we have information of training data, theoretically we can implemented a simpler model to achieve the same performance as the complex model suggested by original VC dimension theory.

Research Project: Cooperative target searching and tracking via UCT with probability distribution model[[PDF]](https://ieeexplore.ieee.org/document/7868620)
======
* School of Automation Science and Electrical Engineering, Beihang University, Beijing, CN, JUL./2015-Dec./2015
* Advisor: Dr. T. Wang
* We developed an online distributed algorithm used in UAVs tracking and searching, with the consideration of UAVs practical need to recharge under limited power. We propose a Quantum Probability Model to describe the partially observable target positions, and we use Upper Confidence Tree (UCT) algorithm to find out the best searching and tracking route based on this model. We also introduce the Teammate Learning Model to handle the non-stationary problems in distributed reinforcement learning.
