---
title: "Laparoscopy Image Enhancement"
excerpt: "A Bayesian Framework for joint removal of surgical smoke, specular highlights, and noise"
collection: research
---

I was a part of the [ViGIL](https://www.cse.iitb.ac.in/graphics/doku.php?id=start) research group at IIT Bombay, where I pursued my thesis under the guidance of  [Prof. Suyash Awate](https://www.cse.iitb.ac.in/~suyash/) and [Prof. Shabbir Merchant](https://www.ee.iitb.ac.in/wiki/faculty/merchant/). We worked on removing random noise, surgical smoke, and speckles from the laparoscopy images. These corruptions perturb the texture and color of the organs, and make the surgical experience unpleasant, and reduce the efficacy of automated algorithms. We modelled the system using Markov random fields, and designed potential functions using color distribution priors and dictionary priors (to model texture). We used variational Bayesian factorization to make the optimization tractable using expectation-maximization (EM) algorithm. 

![Graphical Abstract](/images/lap_graphical_abstract.png)

We had an oral presentation at [IEEE ISBI](https://biomedicalimaging.org/2019/) 2017 ([paper](https://ieeexplore.ieee.org/abstract/document/7950623)). The full thesis can be found [here](/files/lap_thesis.pdf). I was awarded the Undergraduate Research Award 03 (URA-03) for my work.
