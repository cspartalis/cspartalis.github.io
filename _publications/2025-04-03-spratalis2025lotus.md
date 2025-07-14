---
title: "LoTUS: Large-Scale Machine Unlearning with a Taste of Uncertainty"
collection: publications
category: manuscripts
permalink: /publication/2025-04-03-spartalis2025lotus
excerpt: 'We present LoTUS, a novel Machine Unlearning (MU) method that eliminates the influence of training samples from pre-trained models, avoiding retraining from scratch. LoTUS smooths the prediction probabilities of the model up to an information-theoretic bound, mitigating its over-confidence stemming from data memorization. We evaluate LoTUS on Transformer and ResNet18 models against eight baselines across five public datasets. Beyond established MU benchmarks, we evaluate unlearning on ImageNet1k, a large-scale dataset, where retraining is impractical, simulating real-world conditions. Moreover, we introduce the novel Retrain-Free Jensen-Shannon Divergence (RF-JSD) metric to enable evaluation under real-world conditions. The experimental results show that LoTUS outperforms state-of-the-art methods in terms of both efficiency and effectiveness. Code: [https://github.com/cspartalis/LoTUS](https://github.com/cspartalis/LoTUS).
'
date: 2025-04-03
venue: 'Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition'
slidesurl: 'https://cspartalis.github.io/files/cvpr2025_LoTUS_slides.pdf'
paperurl: 'https://cspartalis.github.io/files/Spartalis_LoTUS_Large-Scale_Machine_Unlearning_with_a_Taste_of_Uncertainty_CVPR_2025_paper.pdf'
bibtexurl: 'https://cspartalis.github.io/files/spartalis2025lotus.bib'
citation: 'Spartalis et al. &quot;LoTUS: Large-Scale Machine Unlearning with a Taste of Uncertainty.&quot; <i> In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition</i>. 2025.'
---

We present a **novel Information-Theoretic framework for Machine Unlearning**—a principled method that enables AI models to forget specific training samples by **carefully increasing uncertainty** around them.

Unlike prior approaches that didn’t explore the **information-theoretic nature of unlearning**, our method uses this framework to **discriminate between information that should be forgotten and information that should be retained**, preserving the model’s overall utility while effectively removing targeted data.

### What’s New:
- A **novel Information-Theoretic framework** for defining and guiding machine unlearning.
- A method that **meticulously increases uncertainty** only where needed—efficient and utility-preserving.
- A **new real-world-focused metric** for evaluating unlearning performance in practical deployment scenarios.

### Explore More: [Poster](https://cspartalis.github.io/files/LoTUS_cvpr25_poster_final.pdf) | [Code & Overview](https://github.com/cspartalis/LoTUS)
