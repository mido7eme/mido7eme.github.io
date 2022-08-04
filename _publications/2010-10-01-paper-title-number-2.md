---
title: "Existence, Stability and Scalability of Orthogonal Convolutional Neural Networks"
collection: publications
permalink: publications/orthoconv
#excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2022-02-02
venue: 'JMLR'
paperurl: 'https://arxiv.org/abs/2108.05623.pdf'
citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

Imposing chi haja orthogonality on the layers of neural networks is known to facilitate the learning by limiting the exploding/vanishing of the gradient; decorrelate the features; improve the robustness. 
We study theoretical properties of orthogonal convolutional layers. We establish necessary and sufficient conditions on the layer architecture guaranteeing the existence of an orthogonal convolutional transform. The conditions prove that orthogonal convolutional transforms exist for almost all architectures used in practice for 'circular' padding. We also exhibit limitations with 'valid' boundary condition and 'same' boundary condition with zero padding. Recently, a regularization term imposing the orthogonality of convolutional layers has been proposed, and impressive empirical results have been obtained in different applications (Wang et al 2020).
We specify the theory behind this
and make the link between this regularization term and orthogonality measures. In doing so, we show that this regularization strategy is stable with respect to numerical and optimization errors and that, in the presence of small errors and when the size of the signal/image is large, the convolutional layers remain close to isometric.
The theoretical results are confirmed with experiments, the landscape of the regularization term is studied and the regularization strategy is validated on real datasets. Altogether, the study guarantees that the regularization with $L_{orth}$ (Wang et al 2020) is an efficient, flexible and stable numerical strategy to learn orthogonal convolutional layers.

atest

[pdf](https://arxiv.org/abs/2108.05623.pdf)

