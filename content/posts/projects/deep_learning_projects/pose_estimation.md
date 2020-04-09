---
title: Pose Estimation with High Resolution Neural Networks - A Top-Down Approach
date: 2020-03-30T23:00:00.000+00:00
draft: false
---
[Github link](https://github.com/expectopatronm/pose-estimation-with-high-resolution-neural-networks)

We are interested in the human pose estimation problem with a focus on learning reliable high-resolution representations. Most existing methods recover high-resolution representations from low-resolution representations produced by a high-to-low resolution network. Instead, our proposed network maintains high-resolution representations through the whole process. We start from a high-resolution subnetwork as the first stage, gradually add high-to-low resolution subnetworks one by one to form more stages, and connect the mutli-resolution subnetworks in parallel.

!['Pose Estimation Example'](/images/pose_estimation.gif)