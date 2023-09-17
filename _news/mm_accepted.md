---
layout: post
title: Paper accepted at ACM Multimedia 2023.
date: 2023-07-26
inline: false
related_posts: false
---

Paper titled "Efficient Labelling of Affective Video Datasets via Few-Shot & Multi-Task Contrastive Learning" accepted
ACM Multimedia 2023. 

Preprint version is now online [here](https://arxiv.org/abs/2308.02173).
Code is available [here](https://github.com/ravikiranrao/MTCLAR-FSL)

Abstract: 

>Whilst deep learning techniques have achieved excellent emotion prediction, they still require large amounts of
labelled training data, which are (a) onerous and tedious to compile, and (b) prone to errors and biases.
We propose Multi-Task Contrastive Learning for Affect Representation (**MT-CLAR**) for few-shot affect inference.
MT-CLAR combines multi-task learning with a Siamese network trained via contrastive learning to infer from a pair of
expressive facial images (a) the (dis)similarity between the facial expressions, and (b) the difference in valence and
arousal levels of the two faces. We further extend the image-based MT-CLAR framework for automated video labelling 
where, given one or a few labelled video frames (termed *support-set*), MT-CLAR labels the remainder of the video
for valence and arousal. Experiments are performed on the AFEW-VA dataset with multiple support-set configurations;
moreover, supervised learning on representations learnt via MT-CLAR are used for valence, arousal and categorical
emotion prediction on the AffectNet and AFEW-VA datasets. The results show that valence and arousal predictions via
MT-CLAR are very comparable to the state-of-the-art (SOTA), and we significantly outperform SOTA with a support-set
≈6% the size of the video dataset.


