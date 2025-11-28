---
title: "Unsupervised Band Selection for Hyperspectral Images Classification: Particle Swarm Optimization via Cross-Domain Knowledge Transfer"
collection: publications
category: manuscripts
permalink: /publications/2025-07-01-unsupervised-band-selection-cdkt/
date: 2025-07-01
venue: 'IEEE Transactions on Evolutionary Computation'
paperurl: 'https://academicpages.github.io/files/paper3.pdf'
citation: 'Yuze Zhang, Lingjie Li, Qiuzhen Lin, Ling Wang, Zhong Ming, F Richard Yu, Victor CM Leung. &quot;Unsupervised Band Selection for Hyperspectral Images Classification: Particle Swarm Optimization via Cross-Domain Knowledge Transfer.&quot; <i>IEEE Transactions on Evolutionary Computation</i>. (2025).'
---

Band selection (BS) is a key method in Hyperspectral image (HSI) classification that helps to reduce the computational burden and improve the class separability. However, with the emerging of unmanned aerial vehicle (UAV)-borne HSI datasets, their attributes such as high spatial and spectral resolution as well as large-scale samples pose serious challenges to the existing BS methods, making them inefficient. In addition, the efficient utilization of the prior knowledge from the data collected by fixed UAV-borne sensors in different regions is often easily overlooked. In view of these issues, this paper proposes a neural network-assisted particle swarm optimization (PSO) algorithm for cross-domain BS of UAV-borne HSIs. First, a knowledge learning strategy is designed for the source domain, which applies a neural network model to learn the useful prior knowledge in labeled source domain data. Then, a network-assisted PSO algorithm is introduced to search for the optimal subset of bands in the target domain under the guidance of the valid prior knowledge captured from the source domain by the network model. Moreover, a similarity-based grouping strategy is designed to group similar bands and then select bands from each group with the aims of reducing the redundant information in the subset of bands. Finally, experimental results on three common UAV-borne HSI datasets show that our proposed method can efficiently handle UAV-borne HSI data with large samples, as it is able to find a subset of bands with higher quality compared to several state-of-the-art BS methods.
