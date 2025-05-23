# Finding Optimal Viewpoints for Monocular 3D Human Pose Estimation in Dynamic 3D Gaussian Splatting Space
This repository is the official implementation of "Finding Optimal Viewpoints for Monocular 3D Human Pose Estimation in Dynamic 3D Gaussian Splatting Space" (AVSS, 2025).

## About
Monocular 3D human pose estimation (HPE) focuses on locating 3D joint positions from a single viewpoint. However, it often suffers from viewpoint-dependent depth ambiguities and occlusions, emphasizing that next-best-viewpoint (NBV) selection becomes crucial. Prior work has explored NBV selection, but typically relies on datasets with fixed, discrete camera setups that do not support continuous viewpoint selection or on synthetic environments that lack photorealism. To address these shortcomings, we propose a novel pipeline for NBV selection in monocular 3D HPE. We construct a continuous and photorealistic environment, using 3D Gaussian Splatting (3DGS), which provides continuous novel-view rendering both spatially and temporally. Within this environment, we enable a reinforcement learning (RL) agent to actively select NBVs that minimize pose estimation error. Our approach is evaluated against fixed, random, and rotating camera trajectories, achieving over 24% improvement in pose estimation error.

## Overview
![abstract_figure](https://github.com/user-attachments/assets/baf8faf3-4064-427a-8043-44dcd6a5c8c2)

## Datasets
