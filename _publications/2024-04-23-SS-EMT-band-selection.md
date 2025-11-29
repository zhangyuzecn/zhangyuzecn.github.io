---
title: Superpixel segmentation based evolutionary multitasking algorithm for feature selection of hyperspectral images
collection: publications
category: manuscripts
permalink: /publications/2024-04-23-SS-EMT-band-selection/
date: 2024-04-23
venue: IEEE Transactions on Evolutionary Computation
paperurl: https://ieeexplore.ieee.org/abstract/document/10507166
citation: Lingjie Li, Yuze Zhang, Qiuzhen Lin, Zhong Ming, Carlos A Coello Coello, Victor CM Leung. &quot;Superpixel segmentation based evolutionary multitasking algorithm for feature selection of hyperspectral images.&quot; <i>IEEE Transactions on Evolutionary Computation</i>, vol. 29, no. 4, pp. 1002-1016, 2025.
---

Feature selection (FS) is a very important technique for hyperspectral image (HSI) classification, as successfully selecting informative features can significantly increase the learning performance while reducing the computational cost. However, most of the existing FS methods tend to treat the HSI as a whole for FS, which does not fully consider the unique characteristics of HSIs and disregards the fact that different feature classes possess varying preferences for features. Thus, this article proposes a superpixel segmentation-based evolutionary multitasking (EMT) algorithm for FS of HSIs, called SS-EMT. First, the superpixel segmentation method is used to partition the original HSI into several superpixel blocks, which can preserve well the information of different classes of the original image. Second, in order to explore each superpixel block efficiently, an EMT algorithm using particle swarm optimization is designed, which treats each superpixel block as a subtask and then optimizes these subtasks collaboratively by transferring useful knowledge among related subtasks. In addition, a new individual evaluation mechanism is devised to obtain multiple high-quality feature subsets with different numbers of features simultaneously in a single run, thus reducing the computational cost. Finally, extensive experimental results on four common HSI datasets under three classifiers validate that our proposed method outperforms several state-of-the-art FS methods.