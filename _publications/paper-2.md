---
title: "TP-AE: Temporally Primed 6D Object Pose Tracking with Auto-Encoders"
collection: publications
authors: "Linfang Zheng, Ales Leonardis, Tze Ho Elden Tse, Nora Horanyi, Wei Zhang, Hua Chen, Hyung Jin Chang"
permalink: /publications/paper-2
excerpt: 'Linfang Zheng, Ales Leonardis, Tze Ho Elden Tse, Nora Horanyi, Wei Zhang, Hua Chen, Hyung Jin Chang'
date: 2022-05-23
venue: 'ICRA'
paperurl: 'http://eldentse.github.io/files/ICRA_2022.pdf'
---

### Abstract
Fast and accurate tracking of an object’s motion
is one of the key functionalities of a robotic system for achieving
reliable interaction with the environment. This paper focuses on
the instance-level six-dimensional (6D) pose tracking problem
with a symmetric and textureless object under occlusion. We
propose a Temporally Primed 6D pose tracking framework with
Auto-Encoders (TP-AE) to tackle the pose tracking problem.
The framework consists of a prediction step and a temporally
primed pose estimation step. The prediction step aims to quickly
and efficiently generate a guess on the object’s real-time pose
based on historical information about the target object’s motion.
Once the prior prediction is obtained, the temporally primed
pose estimation step embeds the prior pose into the RGB-D
input, and leverages auto-encoders to reconstruct the target
object with higher quality under occlusion, thus improving the
framework’s performance. Extensive experiments show that the
proposed 6D pose tracking method can accurately estimate the
6D pose of a symmetric and textureless object under occlusion,
and significantly outperforms the state-of-the-art on T-LESS
dataset while running in real-time at 26 FPS.
