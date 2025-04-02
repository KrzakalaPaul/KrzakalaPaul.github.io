---
title: "Any2Graph: Deep End-To-End Supervised Graph Prediction With An Optimal Transport Loss"
collection: publications
permalink: /publication/Any2Graph
excerpt: "A fully diffenrentiable framework for Supervised Graph Prediction"
date: 2024-07-02
venue: "NeurIPS 2024"
slidesurl: 
paperurl: "https://proceedings.neurips.cc/paper_files/paper/2024/hash/b81a352c156ca123c30c740f147a4496-Abstract-Conference.html"
citation: "Krzakala, P., Yang, J., Flamary, R., d'Alché-Buc, F., Laclau, C., & Labeau, M. (2024). Any2Graph: Deep End-To-End Supervised Graph Prediction With An Optimal Transport Loss. Advances in Neural Information Processing Systems, 37, 101552-101588."
---

We propose Any2graph, a generic framework for end-to-end Supervised Graph Prediction (SGP) i.e. a deep learning model that predicts an entire graph for any kind of input. The framework is built on a novel Optimal Transport loss, the Partially-Masked Fused Gromov-Wasserstein, that exhibits all necessary properties (permutation invariance, differentiability and scalability) and is designed to handle any-sized graphs. Numerical experiments showcase the versatility of the approach that outperform existing competitors on a novel challenging synthetic dataset and a variety of real-world tasks such as map construction from satellite image (Sat2Graph) or molecule prediction from fingerprint (Fingerprint2Graph).