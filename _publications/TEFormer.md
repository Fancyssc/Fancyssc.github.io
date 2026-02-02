---
title: "TEFormer: Structured Bidirectional Temporal Enhancement Modeling in Spiking Transformers"
collection: publications
category: conferences
permalink: /publication/TEFormer
excerpt: 'The first brain-inspired bi-directional temporal enhancement on Spiking Transformers.'
date: 2026-01-01
venue: 'arxiv'
citation: "Shen, S., Lv, M., Han, B., Zhao, D., Shen, G., Zhao, F., & Zeng, Y. (2026). TEFormer: Structured Bidirectional Temporal Enhancement Modeling in Spiking Transformers"
paperurl: 'https://arxiv.org/pdf/2601.18274'
---
**Abstract:** 

In recent years, Spiking Neural Networks (SNNs) have achieved remarkable progress, with Spiking Transformers emerging as a promising architecture for energy-efficient sequence modeling. However, existing Spiking Transformers still lack a principled mechanism for effective temporal fusion, limiting their ability to fully exploit spatiotemporal dependencies. Inspired by feedforward-feedback modulation in the human visual pathway, we propose TEFormer, the first Spiking Transformer framework that achieves bidirectional temporal fusion by decoupling temporal modeling across its core components. Specifically, TEFormer employs a lightweight and hyperparameter-free forward temporal fusion mechanism in the attention module, enabling fully parallel computation, while incorporating a backward gated recurrent structure in the MLP to aggregate temporal information in reverse order and reinforce temporal consistency. Extensive experiments across a wide range of benchmarks demonstrate that TEFormer consistently and significantly outperforms strong SNN and Spiking Transformer baselines under diverse datasets. Moreover, through the first systematic evaluation of Spiking Transformers under different neural encoding schemes, we show that the performance gains of TEFormer remain stable across encoding choices, indicating that the improved temporal modeling directly translates into reliable accuracy improvements across varied spiking representations. These results collectively establish TEFormer as an effective and general framework for temporal modeling in Spiking Transformers.

**Code:** [here](https://github.com/Fancyssc/TEFormer)

**Bibtex:**
```angular2html
@misc{shen2026teformerstructuredbidirectionaltemporal,
      title={TEFormer: Structured Bidirectional Temporal Enhancement Modeling in Spiking Transformers}, 
      author={Sicheng Shen and Mingyang Lv and Bing Han and Dongcheng Zhao and Guobin Shen and Feifei Zhao and Yi Zeng},
      year={2026},
      eprint={2601.18274},
      archivePrefix={arXiv},
      primaryClass={cs.NE},
      url={https://arxiv.org/abs/2601.18274}, 
}
```
