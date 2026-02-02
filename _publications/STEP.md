---
title: "STEP: A Unified Spiking Transformer Evaluation Platform for Fair and Reproducible Benchmarking"
collection: publications
category: conferences
#permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'The first Spiking Transformer evaluating models on various datasets and neuron encoding shcemas via unified method."
date: 2025-05
venue: 'NeurIPS 2025'
citation: "Shen, S., Zhao, D., Feng, L., Yue, Z., Li, J., Li, T., ... & Zeng, Y. (2025). STEP: A Unified Spiking Transformer Evaluation Platform for Fair and Reproducible Benchmarking."
paperurl: 'https://arxiv.org/pdf/2505.11151'
---
**Abstract:** 

Spiking Transformers have recently emerged as promising architectures for combining the efficiency of spiking neural networks with the representational power of self-attention. However, the lack of standardized implementations, evaluation pipelines, and consistent design choices has hindered fair comparison and principled analysis. In this paper, we introduce STEP a unified benchmark framework for Spiking Transformers that supports a wide range of tasks, including classification, segmentation, and detection across static, event-based, and sequential datasets. STEP provides modular support for diverse components such as spiking neurons, input encodings, surrogate gradients, and multiple backends (e.g., SpikingJelly, BrainCog). Using STEP, we reproduce and evaluate several representative models, and conduct systematic ablation studies on attention design, neuron types, encoding schemes, and temporal modeling capabilities. We also propose a unified analytical model for energy estimation, accounting for spike sparsity, bitwidth, and memory access, and show that quantized ANNs may offer comparable or better energy efficiency. Our results suggest that current Spiking Transformers rely heavily on convolutional frontends and lack strong temporal modeling, underscoring the need for spike-native architectural innovations. 


**Code:** [here](https://github.com/Fancyssc/STEP)

**Bibtex:**
```angular2html
@article{shen2025step,
  title={STEP: A Unified Spiking Transformer Evaluation Platform for Fair and Reproducible Benchmarking},
  author={Shen, Sicheng and Zhao, Dongcheng and Feng, Linghao and Yue, Zeyang and Li, Jindong and Li, Tenglong and Shen, Guobin and Zeng, Yi},
  journal={arXiv preprint arXiv:2505.11151},
  year={2025}
}
```
