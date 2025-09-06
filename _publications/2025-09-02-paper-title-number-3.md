---
title: "The Quest for the GRAph Level autoEncoder (GRALE)"
collection: publications
permalink: /publication/GRALE
excerpt: "Self-supervised graph representation learning using a trainable graph matching module for computing the reconstruction loss."
date: 2025-05-30
venue: "arXiv preprint"
slidesurl: 
paperurl: "https://arxiv.org/abs/2505.22109"
citation: "Krzakala, P., Melo, G., Laclau, C., d'Alché-Buc, F., & Flamary, R. (2025). The Quest for the GRAph Level autoEncoder (GRALE). arXiv preprint arXiv:2505.22109."
---

Although graph-based learning has attracted a lot of attention, graph representation learning is still a challenging task whose resolution may impact key application fields such as chemistry or biology. To this end, we introduce GRALE, a novel graph autoencoder that encodes and decodes graphs of varying sizes into a shared embedding space. GRALE is trained using an Optimal Transport-inspired loss that compares the original and reconstructed graphs and leverages a differentiable node matching module, which is trained jointly with the encoder and decoder. The proposed attention-based architecture relies on Evoformer, the core component of AlphaFold, which we extend to support both graph encoding and decoding. We show, in numerical experiments on simulated and molecular data, that GRALE enables a highly general form of pre-training, applicable to a wide range of downstream tasks, from classification and regression to more complex tasks such as graph interpolation, editing, matching, and prediction. 