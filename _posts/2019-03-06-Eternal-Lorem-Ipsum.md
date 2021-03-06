---
layout: post
title: Face Normalization
author: Yichen Qian
---

## Unsupervised Face Normalization with Extreme Pose and Expression in the Wild
-----

Face recognition achieves great success thanks to the emergence of deep learning. However, many contemporary face recognition models still have limited invariance to strong intra-personal variations such as large pose changes. Face normalization provides an effective and cheap way to distill face identity and dispell face variance for recognition. We focus on face generation in the wild with unpaired data. To this end, we propose a Face Normalization Model (FNM) to generate a frontal, neutral expression, photorealistic face image for face recognition. FNM is a well-designed Generative Adversarial Network (GAN) with three distinct novelties. First, a face expert network is introduced to construct generator and provide the ability of retaining face identity. Second, with the reconstruction of normal face, a pixel-wise loss is applied to stabilize optimization process. Third, we present a series of face attention discriminators to refine local textures. FNM could recover canonical-view, expression-free image and directly improve the performance of face recognition model. Extensive qualitative and quantitative experiments on both controlled and in-the-wild databases demonstrate the superiority of our face normalization method. 