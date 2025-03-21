---
title: "Multichannel One-Dimensional Data Augmentation with Generative Adversarial Network"
collection: publications
category: manuscripts
permalink: /publication/2023-09-01-paper-title-number-3
excerpt: ''
date: 2023-09-01
venue: ''
paperurl: 'https://www.mdpi.com/1424-8220/23/18/7693'
citation: 'DI Kosasih, BG Lee, H Lim, Multichannel One-Dimensional Data Augmentation with Generative Adversarial Network, Sensors 23 (18), 7693, Sep. 2023.'
---

Data augmentation is one of the most important problems in deep learning. There have been many algorithms proposed to solve this problem, such as simple noise injection, the generative adversarial network (GAN), and diffusion models. However, to the best of our knowledge, these works mainly focused on computer vision-related tasks, and there have not been many proposed works for one-dimensional data. This paper proposes a GAN-based data augmentation for generating multichannel one-dimensional data given single-channel inputs. Our architecture consists of multiple discriminators that adapt deep convolution GAN (DCGAN) and patchGAN to extract the overall pattern of the multichannel generated data while also considering the local information of each channel. We conducted an experiment with website fingerprinting data. The result for the three channels’ data augmentation showed that our proposed model obtained FID scores of 0.005,0.017,0.051 for each channel, respectively, compared to 0.458,0.551,0.521 when using the vanilla GAN.
