---
title: "Content-Aware Rectified Activation for Zero-Shot Fine-Grained Image Retrieval"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Shijie Wang, Jianlong Chang, Zhihui Wang, Haojie Li, Wanli Ouyang, Qi Tian'
date: 2024-01-16
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10404027/'
citation: 'Wang, Shijie, et al. "Content-Aware Rectified Activation for Zero-Shot Fine-Grained Image Retrieval." IEEE Transactions on Pattern Analysis and Machine Intelligence (2024).'
---

Fine-grained image retrieval mainly focuses on learning salient features from the seen subcategories as discriminative embedding while neglecting the problems behind zero-shot settings. We argue that retrieving fine-grained objects from unseen subcategories may rely on more diverse clues, which are easily restrained by the salient features learnt from seen subcategories. To address this issue, we propose a novel Content-aware Rectified Activation model, which enables this model to suppress the activation on salient regions while preserving their discrimination, and spread activation to adjacent non-salient regions, thus mining more diverse discriminative features for retrieving unseen subcategories. Specifically, we construct a content-aware rectified prototype (CARP) by perceiving semantics of salient regions. CARP acts as a channel- wise non-destructive activation upper bound and can be selectively used to suppress salient regions for obtaining the rectified features. Moreover, two regularizations are proposed: 1) a semantic coherency constraint that imposes a restriction on semantic coherency of CARP and salient regions, aiming at propagating the discriminative ability of salient regions to CARP, 2) a feature-navigated constraint to further guide the model to adaptively balance the discrimination power of rectified features and the suppression power of salient features. Experimental results on fine-grained and product retrieval benchmarks demonstrate that our method consistently outperforms the state-of-the-art methods.

