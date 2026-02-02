---
title: "PANDAGUARD: Systematic Evaluation of LLM Safety against Jailbreaking Attacks"
collection: publications
category: conferences
#permalink: /publication/2024-02-17-paper-title-number-4
excerpt: 'We introduce PandaGuard and PandaBench, a unified, reproducible framework and benchmark for systematically evaluating LLM jailbreak attacks, defenses, and judges, revealing that no single defense is universally optimal and that judge disagreement significantly affects safety assessments."
date: 2025-05
venue: 'arxiv'
citation: "Shen, G., Zhao, D., Feng, L., He, X., Wang, J., Shen, S., ... & Zeng, Y. (2025). PANDAGUARD: Systematic Evaluation of LLM Safety against Jailbreaking Attacks."
paperurl: 'https://arxiv.org/pdf/2505.13862'
---
**Abstract:** 

Large language models (LLMs) have achieved remarkable capabilities but remain vulnerable to adversarial prompts known as jailbreaks, which can bypass safety alignment and elicit harmful outputs. Despite growing efforts in LLM safety research, existing evaluations are often fragmented, focused on isolated attack or defense techniques, and lack systematic, reproducible analysis. In this work, we introduce PandaGuard, a unified and modular framework that models LLM jailbreak safety as a multi-agent system comprising attackers, defenders, and judges. Our framework implements 19 attack methods and 12 defense mechanisms, along with multiple judgment strategies, all within a flexible plugin architecture supporting diverse LLM interfaces, multiple interaction modes, and configuration-driven experimentation that enhances reproducibility and practical deployment. Built on this framework, we develop PandaBench, a comprehensive benchmark that evaluates the interactions between these attack/defense methods across 49 LLMs and various judgment approaches, requiring over 3 billion tokens to execute. Our extensive evaluation reveals key insights into model vulnerabilities, defense cost-performance trade-offs, and judge consistency. We find that no single defense is optimal across all dimensions and that judge disagreement introduces nontrivial variance in safety assessments. We release the code, configurations, and evaluation results to support transparent and reproducible research in LLM safety.


**Code:** [here](https://github.com/Beijing-AISI/panda-guard)

**Bibtex:**
```angular2html
@misc{shen2025pandaguardsystematicevaluationllm,
      title={PandaGuard: Systematic Evaluation of LLM Safety against Jailbreaking Attacks}, 
      author={Guobin Shen and Dongcheng Zhao and Linghao Feng and Xiang He and Jihang Wang and Sicheng Shen and Haibo Tong and Yiting Dong and Jindong Li and Xiang Zheng and Yi Zeng},
      year={2025},
      eprint={2505.13862},
      archivePrefix={arXiv},
      primaryClass={cs.CR},
      url={https://arxiv.org/abs/2505.13862}, 
}
```
