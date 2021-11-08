---
title: "Cloudy to Sunny Image Conversion"
excerpt: "Cycle-GAN based network to perform image translation with an additional content similarity loss"
collection: projects
---


 We used cycle-GANs with some modifications in the generator-discriminator architecture and introduced a new content similarity loss to perform image translation between these two classes. The report is hosted [here](/files/cycle-gans.pdf). 



Samples results: For each image pair, the left image is the input cloudy image and the right image is the translated sunny image. Although the results have artifacts, the model has associated certain colors like blue with sky, and yellow/green with plants. Note that all the images have been contrast stretched to the same level.

![Cloudy2SunnyExample](/images/sunnyCloudy.png)

