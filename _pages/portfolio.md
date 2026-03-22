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

<span style="font-size: 1em; color: #6b6b6b;">
Sumegha Premchandar, **Shrijita Bhattacharya**, and Tapabrata Maiti (2023), *Notices of the American Mathematical Society*, 70(07) [[Code](https://github.com/sumegha1024/Normalizing-Flows-Review)].
</span>

{% endcapture %}
<div class="notice--success">{{ gai | markdownify }}</div>

{% capture rlm %}

**Representation Learning with Model Ensembling**

Under this theme, we leverage Bayesian model ensembling to learn intrinsic dimension of images. We use the highest posterior density regions to select the hidden dimensionality of an object. To achieve parallelization across models, we implement a variational Bayes approximation.

**Key Papers**

<span style="font-size: 1em; color: #6b6b6b;">
Zihuan Liu, **Shrijita Bhattacharya**, and Tapabrata Maiti, Variational Bayes Ensemble Learning
Neural Networks With Compressed Feature Space, 2022, *IEEE Transactions on Neural
Networks and Learning Systems*, 1-7 [[Code](https://github.com/shrijitabhattacharya/VB-Ensemble-Learning-NNs)].
</span>

<span style="font-size: 1em; color: #6b6b6b;">
Vojtech Kejzlar, **Shrijita Bhattacharya**, Mookyong Son, Tapabrata Maiti, Black box variational
Bayesian model averaging, 2022, *The American Statistician* 0(0) 1-12 [[Code](https://github.com/kejzlarv/BBVBMA)].
</span>

{% endcapture %}
<div class="notice--success">{{ rlm | markdownify }}</div>

