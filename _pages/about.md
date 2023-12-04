---
permalink: /
title: "Zhihong Shao 邵智宏"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m a final-year Ph.D. student in [Conversational AI Group](http://coai.cs.tsinghua.edu.cn/), Department of Computer Science and Technology, Tsinghua University.
I'm fortunate to be advised by Prof. [Minlie Huang](http://coai.cs.tsinghua.edu.cn/hml).
<!-- Prior to joining CoAI, I received B.E. in Computer Science and Technology from Beihang University. -->

My interests are in natural language processing and deep learning. I am particularly interested in how we can build a robust and scalable AI system that can leverage diverse skills (e.g., tool use and reasoning) to aggregate possibly-heterogeneous information and answer natural language questions precisely regardless of their complexity.

<!-- My recent work has focused on
+ Knowledge-grounded reasoning ([Iter-RetGen](https://arxiv.org/abs/2305.15294) & [RECTIFY](https://arxiv.org/abs/2110.08544))
+ Tool-augmented reasoning ([Synthetic Prompting](https://arxiv.org/abs/2302.00618), [ToRA](https://arxiv.org/abs/2309.17452), [Critic](https://arxiv.org/abs/2305.11738), [CANTOR](https://arxiv.org/abs/2211.16482) & [MIMAX](https://arxiv.org/abs/2106.07174))
+ Robust classification and text matching (e.g., paraphrase detection and natural language inference) ([AdvExpander](https://ieeexplore.ieee.org/document/9622188)) -->

Research Highlights
======
Tool-Augmented Large Language Models
+ Optimize LLM-Tool Interaction and Adapt Tools for LLMs based on the Interaction Data: [Iter-RetGen](https://arxiv.org/abs/2305.15294) with generation-augmented retrieval and generation-augmented retrieval adaptation;
+ Train LLMs to Integrate Tool Use into Generation: [ToRA](https://arxiv.org/abs/2309.17452) (ToRA-34B is the first open-source LLM scoring over 50% on the competition-level MATH dataset);
+ Inference-Time Optimization: (i) Prompt Optimization: [Synthetic Prompting](https://arxiv.org/abs/2302.00618) for automatically synthesizing high-quality CoT demonstrations; (ii) Self-Correction based on Feedback from Tools: [Critic](https://arxiv.org/abs/2305.11738) (Basically the first paper to show that current LLMs struggle with intrinsic self-correction and propose tool-aided correction for more stable improvements).

<!-- Education
======

+ 2019.9 - Present: Ph.D. Student, Department of Computer Science and Technology, Tsinghua University
+ 2015.9 - 2019.6: B.E., Department of Computer Science and Technology, Beihang University -->

Publications
======

+ **Zhihong Shao**, Yeyun Gong, Yelong Shen, Minlie Huang, Nan Duan, and Weizhu Chen\
  **Enhancing Retrieval-Augmented Large Language Models with Iterative Retrieval-Generation Synergy**\
  Findings of Empirical Methods in Natural Language Processing (Findings of EMNLP), 2023.\
  [[Paper]](https://arxiv.org/abs/2305.15294)

+ Zhibin Gou, **Zhihong Shao**, Yeyun Gong, Yelong Shen, Yujiu Yang, Nan Duan, and Weizhu Chen\
  **CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing**\
  Neural Information Processing Systems, Workshop on Agent Learning in Open-Endedness (NeurIPS ALOE Workshop), 2023.\
  [[paper]](https://arxiv.org/abs/2305.11738)/[[code]](https://github.com/microsoft/ProphetNet/tree/master/CRITIC)

+ **Zhihong Shao**, Yeyun Gong, Yelong Shen, Minlie Huang, Nan Duan, and Weizhu Chen\
  **Synthetic Prompting: Generating Chain-of-Thought Demonstrations for Large Language Models**\
  International Conference on Machine Learning (ICML), 2023.\
  [[Paper]](https://arxiv.org/abs/2302.00618)

+ **Zhihong Shao**, Fei Huang, Minlie Huang\
  **Chaining Simultaneous Thoughts for Numerical Reasoning**\
  Findings of Empirical Methods in Natural Language Processing (Findings of EMNLP), 2022.\
  [[Paper]](https://arxiv.org/abs/2211.16482)

+ **Zhihong Shao**, Minlie Huang\
  **Answering Open-Domain Multi-Answer Questions via a Recall-then-Verify Framework**\
  The Annual Meeting of the Association for Computational Linguistics (ACL), 2022.\
  [[Paper]](https://arxiv.org/abs/2110.08544)/[[Code]](https://github.com/ZhihongShao/RECTIFY)\
  (Best QA system on [the AmbigNQ leaderboard](https://nlp.cs.washington.edu/ambigqa/leaderboard.html))

+ **Zhihong Shao**, Zhongqin Wu, Minlie Huang\
  **AdvExpander: Generating Natural Language Adversarial Examples by Expanding Text**\
  Transactions on Audio, Speech, and Language Processing (TASLP), vol. 30, pp. 1184-1196, 2022.\
  [[Paper]](https://ieeexplore.ieee.org/document/9622188)

+ **Zhihong Shao**, Lifeng Shang, Qun Liu, Minlie Huang\
  **A Mutual Information Maximization Approach for the Spurious Solution Problem in Weakly Supervised Question Answering**\
  The Annual Meeting of the Association for Computational Linguistics (ACL), 2021.\
  [[Paper]](https://arxiv.org/abs/2106.07174)/[[Code]](https://github.com/ZhihongShao/MIMAX)

+ **Zhihong Shao**, Minlie Huang, Jiangtao Wen, Wenfei Xu, and Xiaoyan Zhu\
  **Long and Diverse Text Generation with Planning-based Hierarchical Variational Model**\
  Empirical Methods in Natural Language Processing (EMNLP), 2019.\
  [[Paper]](https://arxiv.org/abs/1908.06605)/[[Code]](https://github.com/ZhihongShao/Planning-based-Hierarchical-Variational-Model)

Preprints
======

+ **Zhihong Shao\***, **Zhibin Gou\***, Yeyun Gong, Yelong Shen, Yujiu Yang, Minlie Huang, Nan Duan, and Weizhu Chen\
  **ToRA: A Tool-Integrated Reasoning Agent for Mathematical Problem Solving**\
  Arxiv abs/2309.17452 2023.\
  [[Paper]](https://arxiv.org/abs/2309.17452)/[[Code]](https://github.com/microsoft/tora)\
  (ToRA-34B is the first open-source model that attains an accuracy over 50% on the competition-level MATH dataset)

+ Fei Huang, Dazhen Wan, **Zhihong Shao**, Pei Ke, Jian Guan, Yilin Niu, Xiaoyan Zhu, and Minlie Huang\
  **CoTK: An Open-Source Toolkit for Fast Development and Fair Evaluation of Text Generation**\
  Arxiv abs/2002.00583, 2020.\
  [[Paper]](https://arxiv.org/abs/2002.00583)/[[Code]](https://github.com/thu-coai/cotk)

Selected Honors and Awards
======

+ 1nd Prize, Comprehensive Scholarship, Tsinghua University, 2022
+ 2nd Prize, Comprehensive Scholarship, Tsinghua University, 2021
+ 3rd Prize, the National Final of "LAN QIAO CUP" C/C++ Group, 2018
+ China National Scholarship 2017
+ 1st Prize, National College Students Mathematics Competition (non-math-major), 2016
+ China National Scholarship, 2016

Services
======

Reviewer/Program Committee: ACL, EMNLP, NLPCC, ARR

Teaching
======

I was a TA for the following undergraduate courses:

+ Artificial Neural Network (2019 Fall, 2020 Fall, 2021 Fall, 2022 Fall)
+ Object-Oriented Programming (2020 Spring, 2021 Spring, 2022 Spring)
