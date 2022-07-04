---
title: "S$^2$Contact: Graph-based Network for 3D Hand-Object Contact Estimation with Semi-Supervised Learning"
collection: publications
authors: "Tze Ho Elden Tse**, Zhongqun Zhang**, Kwang In Kim, Ales Leonardis, Hyung Jin Chang"
permalink: /publications/paper-3
excerpt: 'Tze Ho Elden Tse, Zhongqun Zhang*, Kwang In Kim, Ales Leonardis, Hyung Jin Chang'
date: 2022-07-04
venue: 'ECCV'
paperurl: ''
---

### Abstract
Being able to reason about the physical contacts between hands and objects is crucial in understanding hand-object manipulation. However, despite the efforts in accurate 3D annotations in hand and object datasets, there still exist gaps in 3D hand and object reconstructions. Recent works leverage contact maps to refine inaccurate hand-object pose estimations and generate grasps given object models. However, they require explicit 3D supervision which is seldom available and therefore, are limited to constrained settings, e.g., where thermal cameras observe residual heat left on manipulated objects. In this paper, we propose a novel semi-supervised framework that allows us to learn contact from monocular videos. Specifically, we leverage visual and geometric consistency constraints in large-scale datasets for generating pseudo-labels in semi-supervised learning and propose an efficient graph-based network to infer contact. Our semi-supervised learning framework achieves a favourable improvement over the existing supervised learning methods trained on data with ‘limited’ annotations. Notably, our proposed model is able to achieve superior results with less than half the network parameters and memory access cost when compared with the commonly-used PointNet-based approach. We show benefits from using a contact map that rules hand-object interactions to produce more accurate reconstructions. We further demonstrate that training with pseudo-labels can extend contact map estimations to out-of-domain objects and generalise better across multiple datasets.

[Project page]
