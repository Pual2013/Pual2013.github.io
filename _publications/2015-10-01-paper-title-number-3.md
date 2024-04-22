---
title: "Open-set Fine-grained Retrieval via Prompting Vision-Language Evaluator"
collection: publications
permalink: /publication/2015-10-01-paper-title-number-3
excerpt: 'Shijie Wang, Jianlong Chang, Haojie Li, Zhihui Wang, Wanli Ouyang, Qi Tian'
date: 2023-03-04
venue: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition'
paperurl: '[Paper Download](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_Open-Set_Fine-Grained_Retrieval_via_Prompting_Vision-Language_Evaluator_CVPR_2023_paper.html)'
citation: 'Wang, Shijie, et al. "Open-set fine-grained retrieval via prompting vision-language evaluator." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023.'
---

Open-set fine-grained retrieval is an emerging challenge that requires an extra capability to retrieve unknown subcategories during evaluation. However, current works are rooted in the close-set scenarios, where all the subcategories are pre-defined, and make it hard to capture discriminative knowledge from unknown subcategories, consequently failing to handle the inevitable unknown subcategories in open-world scenarios. In this work, we propose a novel Prompting vision-Language Evaluator (PLEor) framework based on the recently introduced contrastive language-image pretraining (CLIP) model, for open-set fine-grained retrieval. PLEor could leverage pre-trained CLIP model to infer the discrepancies encompassing both pre-defined and unknown subcategories, called category-specific discrepancies, and transfer them to the backbone network trained in the close-set scenarios. To make pre-trained CLIP model sensitive to category-specific discrepancies, we design a dual prompt scheme to learn a vision prompt specifying the category-specific discrepancies, and turn random vectors with category names in a text prompt into category-specific discrepancy descriptions. Moreover, a vision-language evaluator is proposed to semantically align the vision and text prompts based on CLIP model, and reinforce each other. In addition, we propose an open-set knowledge transfer to transfer the category-specific discrepancies into the backbone network using knowledge distillation mechanism. A variety of quantitative and qualitative experiments show that our PLEor achieves promising performance on open-set fine-grained retrieval datasets.
