---
title: "GTSfM"
excerpt: "Distributed Structure-From-Motion software"
collection: research
---

Georgia-Tech Structure-From-Motion (GTSfM) is a collaboration between folks at Borglab, Georgia Tech, headed by [Dr. Frank Dellaert](https://dellaert.github.io/). GTSfM is a global SfM pipeline, which utilizes [Dask]() to run in a distributed fashion on a cluster out-of-the-box. The repository is hosted [here](https://github.com/borglab/gtsfm).

I initially started with benchmarking different combinations of **frontend**, which performs feature detection, matching, and verification. With a combination of different deep networks, classical algorithms, and hyperparameters, we benchmarked 15000+ combinations of front-end. To support this 
massive number of experiments, I used dask to parallelize operations on single image (feature detection) and pairs of image (correspondence generation and relative pose recovery) so that I can run my experiments on ~100 machines.
