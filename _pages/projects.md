---
<!-- layout: archive -->
title: "Course Projects"
permalink: /projects/
author_profile: true
---

Face recognition based on deep learning and embedded platform (Undergraduate graduation thesis)
======
* Beihang University, Beijing, CN, Sept./2016-Jun./2017
* Advisor: Professor B. Zhang, School of Automation Science and Electrical Engineering, Beihang University
* I designed a face recognition system based on deep learning and embedded system.
  * Used DSP chip, TMS320DM642 to capture face image from image flow before uploading to computer.
  * Extracted features of face image by using deep convolutional neural network (CNN) and local binary pattern (LBP) operator.
  * Used the features to obtain the identity of the input image by the sparse representation classifier (SRC).
  
Emotion Detector Machine
======
* Columbia University, New York, NY, Sept./2017-Dec./2017
* Course project of Digital Signal Processing
* Lecturer: Professor John Wright, Dept. of Electrical Engineering, Columbia University
* Co-worker: Q. Zheng, M. Li and J. Peng, Graduate Students of Dept. of Electrical Engineering, Columbia University
* We designed an Emotion Detector Machine that can identify the emotion of the input human face by facial expression recognition.
  * Used three different classifiers: K-nearest classifier, support vector machine (SVM) classifier based on HOG and Landmark feature operators and convolutional neural network (CNN) separately to do the emotion detection and compare their results.
  * Adopted Principle Component Analysis (PCA) to do dimension reduction and test the effects of PCA by using SVM classifier on the original dataset and dimension-reduced dataset.

Multi-Digits Recognition based on CNN
======
* Columbia University, New York, NY, Sept./2017-Dec./2017
* Course project of Neural Network & Deep Learning
* Lecturer: Professor Zoran Kostic, Dept. of Electrical Engineering, Columbia University
* Co-worker: J. Li, Graduate Student of Dept. of Electrical Engineering, Columbia University
* We designed architecture that inputs images with multi-digits and outputs the identities of them.
  * Adopted a mixture probability model to represent the length of digits in the original image and every identity of those digits.
  * Built a deep neural network with 8 convolutional layers and 3 fully connected layers by using TensorFlow.
  * Trained and tested the deep neural network with The Street View House Numbers (SVHN) Dataset. Finally we got a 73.998% testing accuracy.
 
Is sparse representation a good and profound explanation for face recognition?
======
* Columbia University, New York, NY, Jan./2018-May./2018
* Course project of Sparse Representation & High-dimensional Geometry
* Lecturer: Professor John Wright, Dept. of Electrical Engineering, Columbia University
* I aimed to figure out whether the sparse representation is a good and profound explanation for face recognition problem.
  * Analyzed Sparse-representation-based algorithm and did experiment on YaleB dataset.
  * Confirmed that the sample space consisting of human face images with different illumination conditions and facial expressions is low-dimensional by calculating the singular values of one sample matrix consisting of images from one arbitrary identity in AR dataset.
  * Did experiment of the Sparse-representation-based algorithm based on AR dataset corrupted by area-sparsed corruptions and showed that the query that the both collaborative representation and 𝑙1 norm minimization are essential to the success of this algorithm.
