---
title: "Collaborative Learning for Hand and Object Reconstruction with Attention-guided Graph Convolution"
collection: publications
authors: "Tze Ho Elden Tse, Kwang In Kim, Ales Leonardis, Hyung Jin Chang"
permalink: /publications/paper-3
excerpt: 'Tze Ho Elden Tse, Kwang In Kim, Ales Leonardis, Hyung Jin Chang'
date: 2022-06-19
venue: 'CVPR'
paperurl: 'http://eldentse.github.io/files/ICSR2019_039_final_v3.pdf'
---

### Abstract
Estimating the pose and shape of hands and objects under interaction finds numerous applications including augmented and virtual reality. Existing approaches for hand and object reconstruction require explicitly defined physical constraints and known objects, which limits its application domains. Our algorithm is agnostic to object models, and it learns the physical rules governing hand-object interaction. This requires automatically inferring the shapes and physical interaction of hands and (potentially unknown) objects. We seek to approach this challenging problem by proposing a collaborative learning strategy where two-branches of deep networks are learning from each other. Specifically, we transfer hand mesh information to the object branch and vice versa for the hand branch. The resulting optimisation (training) problem can be unstable, and we address this via two strategies: (i) attention-guided graph convolution which helps identify and focus on mutual occlusion and (ii) unsupervised associative loss which facilitates the transfer of information between the branches. Experiments using four widely-used benchmarks show that our framework achieves beyond state-of-the-art accuracy in 3D pose estimation, as well as recovers dense 3D hand and object shapes. Each technical component above contributes meaningfully in the ablation study.

[Project page](https://eldentse.github.io/collab-hand-object/)
