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
LLM Multi-Step Reasoning & Tool Augmentation
+ **Improve Math Reasoning with Tool Integration:** [ToRA](https://arxiv.org/abs/2309.17452) (ToRA-34B is the first open-source TOOL-AUGMENTED LLM scoring over 50% on the competition-level MATH dataset);
+ **Improve Math Reasoning via Math Training and RL:** (i) Process-based Reward Model: [Math-Shepherd](https://arxiv.org/abs/2312.08935) for process supervision without human annotations; (ii) Math Training and RL: [DeepSeekMath](https://arxiv.org/abs/2402.03300) (DeepSeekMath 7B is the first open-source LLM scoring over 50% WITHOUT RELYING ON TOOLS on the competition-level MATH dataset);
+ **Improve Formal Math Reasoning with Synthetic Data:** [DeepSeek-Prover](https://arxiv.org/abs/2405.14333) trained on formal math data synthesized by iterating auto-formalization and proof search, which solves 50% of problems from miniF2F-test.;
<!-- + **Optimize LLM-Tool Interaction and Adapt Tools for LLMs based on the Interaction Data:** [Iter-RetGen](https://arxiv.org/abs/2305.15294) with generation-augmented retrieval and generation-augmented retrieval adaptation; -->
+ **Inference-Time Optimization:** (i) Prompt Optimization: [Synthetic Prompting](https://arxiv.org/abs/2302.00618) for automatically synthesizing high-quality CoT demonstrations; (ii) Self-Correction based on Feedback from Tools: [Critic](https://arxiv.org/abs/2305.11738) which shows that current LLMs struggle with intrinsic self-correction and propose tool-aided correction for more stable improvements.

<!-- Education
======

+ 2019.9 - Present: Ph.D. Student, Department of Computer Science and Technology, Tsinghua University
+ 2015.9 - 2019.6: B.E., Department of Computer Science and Technology, Beihang University -->

Publications
======

+ Huajian Xin, Daya Guo, **Zhihong Shao**, Zhizhou Ren, Qihao Zhu, Bo Liu, Chong Ruan, Wenda Li, Xiaodan Liang \
  **DeepSeek-Prover: Advancing Theorem Proving in LLMs through Large-Scale Synthetic Data**\
  The Annual Conference on Neural Information Processing Systems (NeurIPS), MATH-AI workshop, 2024.\
  [[paper]](https://arxiv.org/abs/2405.14333)

+ Peiyi Wang, Lei Li, **Zhihong Shao**, R.X. Xu, Damai Dai, Yifei Li, Deli Chen, Y.Wu, Zhifang Sui\
  **Math-Shepherd: Verify and Reinforce LLMs Step-by-step without Human Annotations**\
  The Annual Meeting of the Association for Computational Linguistics (ACL), 2024.\
  [[paper]](https://arxiv.org/abs/2312.08935)

+ Jiaxin Wen, Ruiqi Zhong, Pei Ke, **Zhihong Shao**, Hongning Wang, Minlie Huang\
  **Assisting Humans For Scalable Oversight by Learning Decomposition From Human Feedback: A Case Study in Competitive Programming**\
  The Annual Meeting of the Association for Computational Linguistics (ACL), 2024.\
  [[paper]](https://openreview.net/pdf?id=A2WwF6b7dW)

+ **Zhihong Shao**, **Zhibin Gou**, Yeyun Gong, Yelong Shen, Yujiu Yang, Minlie Huang, Nan Duan, and Weizhu Chen\
  **ToRA: A Tool-Integrated Reasoning Agent for Mathematical Problem Solving**\
  International Conference on Learning Representations (ICLR), 2024.\
  [[Paper]](https://arxiv.org/abs/2309.17452)/[[Code]](https://github.com/microsoft/tora)\
  (ToRA-34B is the first open-source model that attains an accuracy over 50% on the competition-level MATH dataset)

+ **Zhihong Shao**, Yeyun Gong, Yelong Shen, Minlie Huang, Nan Duan, and Weizhu Chen\
  **Enhancing Retrieval-Augmented Large Language Models with Iterative Retrieval-Generation Synergy**\
  Findings of Empirical Methods in Natural Language Processing (Findings of EMNLP), 2023.\
  [[Paper]](https://arxiv.org/abs/2305.15294)

+ Zhibin Gou, **Zhihong Shao**, Yeyun Gong, Yelong Shen, Yujiu Yang, Nan Duan, and Weizhu Chen\
  **CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing**\
  International Conference on Learning Representations (ICLR), 2024.\
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

+ DeepSeek-AI \
  **DeepSeek-V3 Technical Report**\
  Arxiv abs/2412.19437, 2024.\
  [[paper]](https://arxiv.org/abs/2412.19437)

+ **Huajian Xin**, **Z.Z. Ren**, **Junxiao Song**, **Zhihong Shao**, DeepSeek-AI \
  **DeepSeek-Prover-V1.5: Harnessing Proof Assistant Feedback for Reinforcement Learning and Monte-Carlo Tree Search**\
  Arxiv abs/2408.08152, 2024.\
  [[paper]](https://arxiv.org/abs/2408.08152)

+ **Qihao Zhu**, **Daya Guo**, **Zhihong Shao**, **Dejian Yang**, DeepSeek-AI \
  **DeepSeek-Coder-V2: Breaking the Barrier of Closed-Source Models in Code Intelligence**\
  Arxiv abs/2406.11931, 2024.\
  [[paper]](https://arxiv.org/abs/2406.11931)

+ DeepSeek-AI \
  **DeepSeek-V2: A Strong, Economical, and Efficient Mixture-of-Experts Language Model**\
  Arxiv abs/2405.04434, 2024.\
  [[paper]](https://arxiv.org/abs/2405.04434)

+ **Zhihong Shao**, Peiyi Wang, Qihao Zhu, Runxin Xu, Junxiao Song, Mingchuan Zhang, Y.K. Li, Y. Wu, Daya Guo \
  **DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models**\
  Arxiv abs/2402.03300, 2024.\
  [[paper]](https://arxiv.org/abs/2402.03300)/[[code]](https://github.com/deepseek-ai/DeepSeek-Math)

+ DeepSeek-AI \
  **DeepSeek LLM: Scaling Open-Source Language Models with Longtermism**\
  Arxiv abs/2401.02954, 2024.\
  [[paper]](https://arxiv.org/abs/2401.02954)/[[code]](https://github.com/deepseek-ai/DeepSeek-LLM)

+ Fei Huang, Dazhen Wan, **Zhihong Shao**, Pei Ke, Jian Guan, Yilin Niu, Xiaoyan Zhu, and Minlie Huang\
  **CoTK: An Open-Source Toolkit for Fast Development and Fair Evaluation of Text Generation**\
  Arxiv abs/2002.00583, 2020.\
  [[Paper]](https://arxiv.org/abs/2002.00583)/[[Code]](https://github.com/thu-coai/cotk)

Selected Honors and Awards
======

+ Lenovo Scholarship, Tsinghua University, 2023
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
