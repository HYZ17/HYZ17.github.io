---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I am a second-year PhD student in [The Hong Kong University of Science and Technology](https://hkust.edu.hk), [Department of Computer Science and Engineering](https://cse.hkust.edu.hk). I am fortunate to be advised by Prof. [Junxian He](https://jxhe.github.io/). Before that, I received the bachelor degree in Computer Science in [Shanghai Jiao Tong University](https://en.sjtu.edu.cn/) in 2023. 

## Research Interests
I am primarily focused on large language models, particularly in advancing their reasoning capabilities and multimodal understanding. To achieve this, my research interests lie in: 
* Enhancing reasoning and planning abilities through self-improvement and RL techniques. (**B-STaR**, **SimpleRL**)
* Developing reliable evaluation methods for language models. (**C-Eval**, **LLM-Compression-Intelligence**)
* Improving the architecture and training methods of multimodal models to strengthen their understanding across multiple modalities.

I am open to any collaboration 🤗

## Selected Publications
Most recent publications on [Google Scholar](https://scholar.google.com/citations?user=XZK8cewAAAAJ&hl=en).  \\
\* denotes co-first authors

**SimpleRL-Zoo: Investigating and Taming Zero Reinforcement Learning for Open Base Models in the Wild**\\
Weihao Zeng \*, *<ins>Yuzhen Huang</ins>* \*, Qian Liu \*, Wei Liu, Keqing He, Zejun Ma, Junxian He\\
COLM 2025. [[arxiv]](https://arxiv.org/abs/2503.18892) [[github]](https://github.com/hkust-nlp/simpleRL-reason) [[Hugging Face]](https://huggingface.co/collections/hkust-nlp/simplerl-zoo-67e0fd24c185423c1e3452d1)
* Achieve improvements in both reasoning accuracy and response length across diverse models.
* Introduce SimpleRL-Zoo, a simple reinforcement learning recipe to improve models’ reasoning abilities.
* Identify key factors that shape the emergence of advanced reasoning behaviors (i.e., the “aha moment”).

**SimpleRL: 7B Model and 8K Examples: Emerging Reasoning with Reinforcement Learning is Both Effective and Efficient**\\
Weihao Zeng \*, *<ins>Yuzhen Huang</ins>* \*, Wei Liu, Keqing He, Qian Liu, Zejun Ma, Junxian He\\
Notion. [[notion]](https://hkust-nlp.notion.site/simplerl-reason) [[github]](https://github.com/hkust-nlp/simpleRL-reason/tree/v0) [[Hugging Face]](https://huggingface.co/collections/hkust-nlp/simplerl-67b543892b2ec6908ffff710)
* Training on a 7B model using only 8K MATH examples, achieving strong performance in complex mathematical reasoning.
* Demonstrated that a 7B model develops long CoT and self-reflection through RL with a simple design.
* Outperforms methods that use over 50× more data and complex architectures.


**Predictive Data Selection: The Data That Predicts Is the Data That Teaches**\\
Kashun Shum \*, *<ins>Yuzhen Huang</ins>* \*, Hongjian Zou, Ding Qi, Yixuan Liao, Xiaoxin Chen, Qian Liu, Junxian He\\
ICML 2025. [[arxiv]](https://arxiv.org/abs/2503.00808) [[github]](https://github.com/hkust-nlp/PreSelect) [[dataset]](https://huggingface.co/datasets/hkust-nlp/PreSelect-100B)
* Leverages compression efficiency to identify high-quality data that enhances downstream performance.
* Introduces PRESELECT, a lightweight data selection method based on predictive strength.
* Demonstrates a 10x reduction in compute requirements and significant performance improvements.


**B-STaR: Monitoring and Balancing Exploration and Exploitation in Self-Taught Reasoners**\\
Weihao Zeng \* , *<ins>Yuzhen Huang</ins>* \*, Lulu Zhao, Yijun Wang, Zifei Shan, Junxian He\\
ICLR 2025. [[arxiv]](https://arxiv.org/abs/2412.17256) [[github]](https://github.com/hkust-nlp/B-STaR) 
* Quantitatively analyze the dynamics of exploration and exploitation during self-improvement.
* Introduce B-STaR, a Self-Taught Reasoning framework that autonomously adjusts its configurations.
* Balance exploration and exploitation, leading to superior performance.


**Compression Represents Intelligence Linearly** \\
*<ins>Yuzhen Huang</ins>* \*, Jinghan Zhang *, Zifei Shan, Junxian He\\
COLM 2024. [[arxiv]](https://arxiv.org/abs/2404.09937) [[github]](https://github.com/hkust-nlp/llm-compression-intelligence) [[dataset]](https://huggingface.co/datasets/hkust-nlp/llm-compression)
* Investigate the linear correlation between compression and intelligence in LLMs.
* Provide evidence for the belief that superior compression is indicative of greater intelligence.
* Propose compression efficiency serves as an unsupervised and reliable metric to assess LLMs’ abilities.


**C-Eval: A Multi-Level Multi-Discipline Chinese Evaluation Suite for Foundation Models**\\
*<ins>Yuzhen Huang</ins>* \*, Yuzhuo Bai *, Zhihao Zhu, Junlei Zhang, Jinghan Zhang, Tangjun Su, Junteng Liu, Chuancheng Lv, Yikai Zhang, Jiayi Lei, Yao Fu, Maosong Sun, Junxian He\\
NeurIPS 2023 (Datasets and Benchmarks track). [[arxiv]](https://arxiv.org/abs/2305.08322) [[github]](https://github.com/hkust-nlp/ceval) [[website]](https://cevalbenchmark.com) [[dataset]](https://huggingface.co/datasets/ceval/ceval-exam)
* The first comprehensive Chinese evaluation suite for LLMs.
* Conduct a thorough evaluation of the most advanced LLMs.
* Over 9.8M downloads on Hugging Face and more than 100 models on leaderboard.



## Experiences
### Academia
- *2024.02 - now* PhD student, Department of CSE, [HKUST](https://hkust.edu.hk), Hong Kong SAR, China.
- *2019.09 - 2023.06* Undergraduate, Computer Science, [Shanghai Jiao Tong University](https://en.sjtu.edu.cn/), Shanghai, China.

### Industry
- *2025.01 - Present* Intern Research scientist, TikTok AI Innovation Center, Singapore
- *2023.11 - 2024.01* Research Intern, Wechat, Tencent.

## Service
Reviewer: NeurIPS 2024, ICLR 2025, ICML 2025, NeurIPS 2025, ARR

## Invited Talks

* Mar 2025, Georgia Tech PAIR, *Emerging Reasoning with Reinforcement Learning is Both Effective and Efficient.* 
* Feb 2025, Apple AIML, *Emerging Reasoning with Reinforcement Learning is Both Effective and Efficient.* 
* May 2024, BAAI, *Compression Represents Intelligence Linearly.* [[video]](https://event.baai.ac.cn/activities/784)