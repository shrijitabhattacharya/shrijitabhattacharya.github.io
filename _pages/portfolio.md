---
layout: archive
title: "Research"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}


Highlighted Research Contributions
======

{% capture gai %}

**Recovery of Bayesian Posteriors with Generative AI**

Under this theme, we leverage generative models (normalizing flows in particular) to generate posteriors arising from complex statistical models. We provide theoretical 
guarantees of the credible coverage while ensuring scalable implementation with variational inference.

**Key Papers**

<span style="font-size: 0.9em; color: #6b6b6b;">
Sumegha Premchandar, **Shrijita Bhattacharya**, and Tapabrata Maiti (2023), *Notices of the American Mathematical Society*, 70(07) [[Code](https://github.com/sumegha1024/Normalizing-Flows-Review)].
</span>

{% endcapture %}
<div class="notice--info">{{ gai | markdownify }}</div>

{% capture rlm %}

**Representation Learning with Model Ensembling**

Under this theme, we leverage Bayesian model ensembling to learn intrinsic dimension of images. We use the highest posterior density regions to select the hidden dimensionality of an object. To achieve parallelization across models, we implement a variational Bayes approximation. We were able to achieve a 10% compression on MNIST image data and an 18% compression on Fashion-MNIST.

**Key Papers**

<span style="font-size: 0.9em; color: #6b6b6b;">
Zihuan Liu, **Shrijita Bhattacharya**, and Tapabrata Maiti, Variational Bayes Ensemble Learning
Neural Networks With Compressed Feature Space, 2022, *IEEE Transactions on Neural
Networks and Learning Systems*, 1-7 [[Code](https://github.com/shrijitabhattacharya/VB-Ensemble-Learning-NNs)].
</span>

<span style="font-size: 0.9em; color: #6b6b6b;">
Vojtech Kejzlar, **Shrijita Bhattacharya**, Mookyong Son, Tapabrata Maiti, Black box variational
Bayesian model averaging, 2022, *The American Statistician* 0(0) 1-12 [[Code](https://github.com/kejzlarv/BBVBMA)].
</span>

{% endcapture %}
<div class="notice--success">{{ rlm | markdownify }}</div>

{% capture dnn %}

** Low-latency Deep Neural Networks with Spike-and-slab**

Under this theme, we use spike and slab shrinkage priors like Gaussian, Lasso and Horse-shoe for selecting useful neurons in a data-adaptive approach. We contrast the performance of these three priors in asymptotic performance and time complexity of implementation. We reduced the deployment time of
a classification model on Fashion-MNIST dataset by 20% and on CIFAR-10 dataset by 10%.


**Key Papers**

<span style="font-size: 0.9em; color: #6b6b6b;">
Sanket Jantre, **Shrijita Bhattacharya**, Tapabrata Maiti, Spike-and-slab shrinkage priors for
structurally sparse Bayesian neural networks, 2024, *IEEE Transactions on Neural Networks
and Learning Systems* 36 (6), 11176-11188. [[Code](https://github.com/jsanket12/SS_Group_Shrinkage_New)].
</span>

<span style="font-size: 0.9em; color: #6b6b6b;">
Sanket Jantre, **Shrijita Bhattacharya**, Tapabrata Maiti, Layer Adaptive Node Selection in
Bayesian Neural Networks: Statistical Guarantees and Implementation Details, 2021, *Neural
Networks* 167, 309-330. [[Code](https://github.com/jsanket12/SS_IG)].
</span>


{% endcapture %}
<div class="notice--warning">{{ dnn | markdownify }}</div>

{% capture isn %}

** Binary Graphical Models aided Variable Selection**

Under this theme, we have exploited Ising distributions to capture the graphical structure among binary variables. This allowed for high dimensional variable selection, especially when the predictors share a network structure. A variational Bayes algorithm providing 200X speed over Gibbs sampling was developed.

**Key Papers**


<span style="font-size: 0.9em; color: #6b6b6b;">
Siddhartha Nandy, Minwoo Kim, **Shrijita Bhattacharya**, Tapabrata Maiti, Variational inference
aided variable selection for spatially structured high dimensional covariates, 2025,
*Journal of Computational and Graphical Statistics* 35 (1), 482-493 [[Code](https://github.com/shrijitabhattacharya/VI-aided-variable-selection-with-Ising)].
</span>

<span style="font-size: 0.9em; color: #6b6b6b;">
Minwoo Kim, **Shrijita Bhattacharya**, Tapabrata Maiti, Statistically valid variational bayes
algorithm for Ising model parameter estimation, 2024, *Journal of Computational and Graphical
Statistics* 33(1), 75-84. [[Code]](https://github.com/stat-kim/vb-Ising).
</span>


{% endcapture %}
<div class="notice--warning">{{ isn | markdownify }}</div>





