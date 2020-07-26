---
title: "Learning from Macro-expression: an Adversarial Micro-expression Recognition Framework[[PDF]](http://Wei-kang-Wang.github.io/files/Micro-paper.pdf)"
collection: 
permalink: /publications/Micro
venue: "Admitted by ACM Multimedia 2020"
date: 2020-06-15
citation: '<b>Wei-kang Wang</b>, Bin Xia, Shangfei Wang and Enhong Chen.'
---
## Abstract
As one of the most important forms of psychological behaviors, micro-expression can reveal the real emotion. However, the existing labeled micro-expression samples are limited to train a high performance micro-expression classifier. Since micro-expression and macro-expression share some similarities in facial muscle movements and texture changes, in this paper we propose a microexpression recognition framework that leverages macro-expression samples as guidance. Specifically, we first introduce two Expression-Identity Disentangle Network, named MicroNet and MacroNet, as the feature extractor to disentangle expression-related features for micro and macro expression samples. Then MacroNet is fixed and used to guide the fine-tuning of MicroNet from both label and feature space. Adversarial learning strategy and triplet loss are added upon feature level between the MicroNet and MacroNet, so the MicroNet can efficiently capture the shared features of microexpression and macro-expression samples. Loss inequality regularization is imposed to the label space to make the output of MicroNet converge to that of MicroNet. Comprehensive experiments on three public spontaneous micro-expression databases, i.e., SMIC, CASME2 and SAMM  demonstrate the superiority of the proposed method.
