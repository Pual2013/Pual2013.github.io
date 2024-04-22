---
title: "Accurate Fine-grained Object Recognition with Structure-driven Relation Graph Networks"
collection: publications
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'Shijie Wang, Zhihui Wang, Haojie Li, Jianlong Chang, Wanli Ouyang, Qi Tian'
date: 2023-07-30
venue: 'International Journal of Computer Vision (IJCV)'
paperurl: ‘[Paper Download](https://link.springer.com/article/10.1007/s11263-023-01873-z)‘
citation: 'Wang, Shijie, et al. "Accurate fine-grained object recognition with structure-driven relation graph networks." International Journal of Computer Vision 132.1 (2024): 137-160.'
---

Fine-grained object recognition (FGOR) aims to learn discriminative features that can identify the subtle distinctions between visually similar objects. However, less effort has been devoted to overcoming the impact of object’s personalized differences, e.g., varying posture or perspective. We argue that the personalized differences could decline the network’s perception of discriminative features, thus discarding some discriminative clues and degrading the FGOR performance accordingly. This motivates us to explore the intrinsic structure knowledge: the fixed spatial correlation between object parts, and thus apply this knowledge to associate diverse semantic parts and recover the missing discriminative details caused by the personalized differences accordingly. In this paper, we propose an end-to-end Structure-driven Relation Graph Network (SRGN) for fine-grained object recognition, and target at exploring and exploiting the object structure information without any additional annotations to associate diverse semantic parts, making the network sensitive to discriminative details influenced by personalized differences. Specifically, the core of SRGN is a Structure-aware Axial Graph (SAG) module, which first infers the structure embedding by establishing the correlation between position information and visual features along the axial direction, and then applies this embedding as aggregation weights to emphasize each discriminative representation by weighted reassembling all relevant features to it. Additionally, our SAG can be readily extensible to a multi-graph schema, that leverages the complementary advantages of different structure embeddings between the position information and visual content, further improving SAG. In this way, our SRGN can demonstrate remarkable robustness in scenarios characterized by extreme distribution perturbations, ultimately leading to superior performance. Extensive experiments and explainable visualizations validate the efficacy of the proposed approach on widely-used fine-grained benchmarks.


