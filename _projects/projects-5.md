---
title: "Computational Photography "
excerpt: "Collections of projects and assignments"
collection: projects
---

## Video stabilization
Developed a video stabilization algorithm with the following steps:
1. Similarity motion model estimation between frames using optical flow features
2. Used a simple full-body detector to extract salient point per frame and added constraints for the salient point to 
be in the frame.
3. Formulated a linear program using motion smoothness and saliency constraints.

A sample motion model with the before (blue) and after (yellow) motion:
![sample_motion_model](/images/cp/video_stabilization_motion_model.png)

## Panorama Generation
I used SIFT features to fit homography motion models between frames and performed blending in the alpha channel to generate panoramas. 
A sample result is presented below:

Inputs:
![inp_1](/images/cp/pano_inp_1.jpg)
![inp_2](/images/cp/pano_inp_2.jpg)
![inp_3](/images/cp/pano_inp_3.jpg)

Output:
![output](/images/cp/pano_output.jpg)