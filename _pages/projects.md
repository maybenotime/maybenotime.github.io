---
layout: archive
permalink: /projects/
title: "Projects"
author_profile: true
---


CCL2022 Evaluation Task — The fourth NiuTrans Cup humor computing [\[Code\]](https://github.com/maybenotime/CCL2022_humor_computing)
======
* This evaluation task is divided into two tracks: humor recognition and humor response generation in dialogue scenarios. We rank top at both tracks and win the First Prize finally.
* For humor recognition, we explore sentence-based text classification, dialogue modeling, and prompt-based text classification. We conduct experiments using various BERT variants and apply a range of tricks. Then, we ensemble heterogeneous models through a stacking approach to further improve the performance.
* For humor response generation, we design a sliding window strategy to perform data augmentation and conduct experiments on GPT2 and T5. Furthermore, we utilize the humor recognition model to select humorous response from sampled results.

Hard-Constrained Text Generation with Controllable Word Complexity (Thesis) [\[Code\]](https://github.com/maybenotime/BLCU2022_Undergraduate_Thesis)
======
* We introduce hard-constrained text generation and style transfer to the field of international Chinese language education, generating example sentences based on user-entered keywords with controllable word complexity.
* We employ the T5 model to generate example sentences in a fill-in-the-blank way, ensuring that the generated sentences include all the keywords.
* We propose an unsupervised method to mine training data automatically from corpus. And we train the model using prompt tuning instead of standard fine-tuning to achieve style transfer at a lower cost.
Reverse Dictionary in Chinese
======
* We explore both classification and generation methods for the reverse dictionary task. Furthermore, we construct a private validation dataset using company data to choose models.
* We replicate the method proposed by «BERT for Monolingual and Cross-Lingual Reverse Dictionary» and improve its performance by injecting external knowledge.
* We retrieve similar samples from training data to augment user input, bridging the gap between user input and training data.

