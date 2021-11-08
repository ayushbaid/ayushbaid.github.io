---
title: "3D object detection from arbitrary RGB camera rigs"
excerpt: "Detecting cars from RGB input for self-driving applications."
collection: research
---

Most self-driving cars have a set of RGB cameras on the vehicle. 
We tried to use these camera rigs for 3D object detection. As different self-driving companies have different number of
cameras on the rigs and different layouts, we based our deep network on a trajectory planning network Lift-Splat-Shoot
which works on arbitrary rigs too.

We also experimented with using LiDAR as privileged information (i.e. just used during training). 
Privileged information has been used to improve the performance and reduce training time. We observed performance gains
upto a handful of epochs, but the gains disappeared after ~10 epochs.

A [report](/files/3d_detection/report.pdf) and a [short presentation](/files/3d_detection/presentation.pdf) is 
available for further reading.

These are the two detection outputs from the RGB-only trained network and RGB+PI network.

| RGB only training and inference | RGB + LiDAR training / RGB only inference|
| ------------------------------  | ------------------------------------ |
| ![1_rgb](/images/3d_detection/detection-1_rgbonly.png) | ![1_pi](/images/3d_detection/detection-1_rgbpi.png) |
| ![2_rgb](/images/3d_detection/detection-2_rgbonly.png) | ![2_pi](/images/3d_detection/detection-2_rgbpi.png) |

