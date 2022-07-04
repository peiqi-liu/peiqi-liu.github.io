---
date: 2018-09-09 23:16:20
layout: research
tags: robust ml, deep neural network, verification, co-training
description: ReLU Stability
title: Training for Faster Adversarial Robustness Verification via Inducing ReLU Stability
authors: "Kai Y. Xiao, Vincent Tjeng, Nur Muhammad (Mahi) Shafiullah, Aleksander Madry"
code_url: https://github.com/MadryLab/relu_stable
paper_url: https://arxiv.org/abs/1809.03008
show_blog_link: false
venue: International Conference of Learning Representations (ICLR) 2019
local_video: assets/images/research/rsloss.webm
---

We explore the concept of co-design in the context of neural network verification. Specifically, we aim to train deep neural networks that not only are robust to adversarial perturbations but also whose robustness can be verified more easily. To this end, we identify two properties of network models - weight sparsity and so-called ReLU stability - that turn out to significantly impact the complexity of the corresponding verification task. We demonstrate that improving weight sparsity alone already enables us to turn computationally intractable verification problems into tractable ones. Then, improving ReLU stability leads to an additional 4-13x speedup in verification times. An important feature of our methodology is its "universality," in the sense that it can be used with a broad range of training procedures and verification approaches. 