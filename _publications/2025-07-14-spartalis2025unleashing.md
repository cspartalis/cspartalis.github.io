title: "Unleashing Uncertainty: Efficient Machine Unlearning for Generatice AI"
collection: publications
category: manuscripts
permalink: /publication/2025-04-03-spartalis2025lotus
excerpt: 'We introduce SAFEMax, a novel method for Machine Unlearning in diffusion models. Grounded in information-theoretic principles, SAFEMax maximizes the entropy in generated images, causing the model to generate Gaussian noise when conditioned on impermissible classes by ultimately halting its denoising process. Also, our method controls the balance between forgetting and retention by selectively focusing on the early diffusion steps, where class-specific information is prominent. Our results demonstrate the effectiveness of SAFEMax and highlight its substantial efficiency gains over state-of-the-art methods.
'
date: 2025-07-14
venue: 'ICML 2025 Workshop on Machine Unlearning for Generative AI'
paperurl: 'https://cspartalis.github.io/files/icml2025_Unleashing_Uncertainty_Efficient_Machine_Unlearning_for_Generative_AI.pdf'
bibtexurl: 'https://cspartalis.github.io/files/spartalis2025unleashing.bib'
citation: 'Spartalis et al. &quot;Unleashing Uncertainty: Efficient Machine Unlearning for Generative AI.&quot; <i> ICML 2025 Workshop on Machine Unlearning for Generative AI</i>. 2025.'
---

This paper is an extension of our CVPR2025 machine unlearning paper. There, we proposed an **information-theoretical** framework in an attempt to discriminate the information to be unlearned and the one to be retained, and a novel method, called **LoTUS**, that succeeded effective and efficient unlearning by increasing the model's uncertainty about the data to be forgotten. Our previous work focused on classifiers.

In this paper we are presenting a brief overview of our novel method, **SAFEMax** that is guided by the **information-theoretical** foundation we have developed for machine unlearning. Preliminary experiments demonstrate that SAFEMax:
- succeeds significantly more efficient unlearning than existing methods,
- leverages the internal mechanisms and attributes of DDPMs in an attempt to minimize the priors needed for unlearning.

The research questions that arise are:
- Do we really need to anchor forgotten concepts/classes to other ones?
- Does unleashing uncertainty enhances the robustness of unlearning, in terms of resilience to unlearning attacks that attempt to restore the forgotten information?

### Explore More: [Poster](https://cspartalis.github.io/files/A1_PosterICML.pdf)
