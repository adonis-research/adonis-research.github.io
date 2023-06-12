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
Modern state-of-the-art Machine Learning models, like Deep Neural Networks, require a substantial amount of computing power to achieve top performance. For example, a particular bottleneck for language models such as GPT-3 is that while their performance increases with the model's statistical capacity, their memory requirements become impractical for most single computers. Until recently, the focus has been on developing more powerful hardware and structuring them into finely tuned cluster servers. Specifically, the goal was to improve hardware capacity while ensuring compatibility (or requiring minimal code modification) to allow researchers to focus on training algorithms and numerical dynamics. The ADONIS project takes a radically different research direction by attempting to exploit a weakly reliable but gigantic network of heterogeneous computing devices whose topology may vary over time. In short, we not only want the Internet of Things to provide more information but also more computing power. Finally, optimizing the usage of a large heterogeneous cluster by discarding any computation that does not contribute to the final performance will decrease the overall energy impact of modern deep learning.


---

## Decentralized Convex Optimization

Before tackling the practical challenges related to parallelizing the training of advanced Machine Learning models, which is primarily based on empirical evidence, the ADONIS project first investigates convex optimization, a domain with well-established theoretical foundations. By deriving necessary and sufficient conditions for decentralized optimization, we gain valuable theoretical insights into the technical limitations of decentralized approaches. Additionally, this setting allows us to compare the theoretical expectations of algorithms with their practical performance on real-world heterogeneous clusters.

---

## Decentralized Training of Deep Neural Networks

Neural Networks provides state-of-the-art results in many areas, but most research contributions requires significant and reliable computing power. Instead of adapting the hardware to match the prohibitively increasing computing power needed to train large models, this project aims to identify architectures, objective functions and optimization procedures compatible with a given cluster of heterogeneous devices. Training deep architectures in this setting allows evaluating to which extent the results obtained in decentralized convex optimization translates in the non-convex case. Furthermore, transposing some engineering tricks commonly employed in deep learning such as batch-normalization is not straightforward. One goal of the ADONIS project is to manage such technical limitations without substantial drop in empirical model performance.

---

## Common Framework for Proper Benchmarking

As is often the case with cutting edge research, there are few but very specialized contributions and a lack of unifying theoretical framework to handle decentralized optimization. One key ingredient that allowed computer vision to improve the practical relevance of research contributions has been to set common benchmarks. A key aspect of this project is thus to derive a set of objective evaluation methods, enabling a fair comparison between scientific contributions in decentralized optimization. It is crucial for such cutting edge research to understand why some principled ideas do not match their theoretical potential, or to identify which aspect of a peculiar engineering trick actually increases a model performance.
