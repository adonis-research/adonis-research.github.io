---
layout: page
permalink: /objectives/
title: Objectives
description: Motivation and objectives of the ADONIS project.
nav: true
nav_order: 2
---

## Motivations

<style> body {text-align: justify} </style>
Modern state-of-the-art Machine Learning models, like Deep Neural Networks, requires a substantial amount of computing power to achieve top performances. For example, a particular bottleneck for language models such as GPT-3 is that while their performance increases with the model statistical capacity, its memory requirements become impractical for most single computer. Until recently, the focus has been directed on developing more powerful hardware and structuring them into a finely tuned cluster server. More precisely, the goal was to improve the hardware capacity while making it compatible (or requiring minimal code modification) to let researchers focus on training algorithms and numerical dynamics. The ADONIS project takes a radically different research direction by trying to exploit a weakly reliable but gigantic network of heterogeneous computing devices whose topology may vary in time. For short, we not only want the Internet of Things to provide more information, but also more computing power. Finally, optimizing the usage of a large heterogeneous cluster by discarding any computation which does not contribute to the final performance will decrease the overall energetic impact of modern deep learning.


---

## Decentralized Convex Optimization

Before addressing the practical issues associated with the parallelization of training advanced Machine Learning models for which our understanding mainly comes from empirical evidence, the ADONIS project explores convex optimization, whose theory is much better understood. Deriving necessary or sufficient conditions for decentralized optimization gives theoretical insights on the technical limitations of decentralized optimization. Furthermore, it is a setting where one can compare the theoretical expectation of an algorithm with its practical performance on a real world heterogeneous cluster.

---

## Decentralized Training of Deep Neural Networks

Neural Networks provides state-of-the-art results in many areas, but most research contributions requires significant and reliable computing power. Instead of adapting the hardware to match the prohibitively increasing computing power needed to train large models, this project aims to identify architectures, objective functions and optimization procedures compatible with a given cluster of heterogeneous devices. Training deep architectures in this setting allows evaluating to which extent the results obtained in decentralized convex optimization translates in the non-convex case. Furthermore, transposing some engineering tricks commonly employed in deep learning such as batch-normalization is not straightforward. One goal of the ADONIS project is to manage such technical limitations without substantial drop in empirical model performance.

---

## Common Framework for Proper Benchmarking

As is often the case with cutting edge research, there are few but very specialized contributions and a lack of unifying theoretical framework to handle decentralized optimization. One key ingredient that allowed computer vision to improve the practical relevance of research contributions has been to set common benchmarks. A key aspect of this project is thus to derive a set of objective evaluation methods, enabling a fair comparison between scientific contributions in decentralized optimization. It is crucial for such cutting edge research to understand why some principled ideas do not match their theoretical potential, or to identify which aspect of a peculiar engineering trick actually increases a model performance.
