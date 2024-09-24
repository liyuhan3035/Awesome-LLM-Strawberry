# Awesome LLM Strawberry (OpenAI o1)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)  ![visitor badge](https://visitor-badge.lithub.cc/badge?page_id=hijkzzz.awesome-llm-strawberry&left_text=Visitors) ![GitHub stars](https://img.shields.io/github/stars/hijkzzz/Awesome-LLM-Strawberry?color=yellow) ![GitHub forks](https://img.shields.io/github/forks/hijkzzz/Awesome-LLM-Strawberry?color=9cf) [![GitHub license](https://img.shields.io/github/license/hijkzzz/Awesome-LLM-Strawberry)](https://github.com/hijkzzz/Awesome-LLM-Strawberry/blob/main/LICENSE)

This is a collection of research papers & blogs for **OpenAI Strawberry(o1) and Reasoning**.

And the repository will be continuously updated to track the frontier of LLM Reasoning.

## OpenAI Docs
- [https://platform.openai.com/docs/guides/reasoning](https://platform.openai.com/docs/guides/reasoning)
- <img src="https://github.com/user-attachments/assets/b165cb20-9202-4951-8783-6b2f7e0d6071" width="600px">


## Blogs

- [OpenAI] [Learning to Reason with LLMs](https://openai.com/index/learning-to-reason-with-llms/)
- 概述：这篇博客介绍了OpenAI o1的训练方法，其中包括链式推理、自我批评、验证、多步骤推理、任务分解和蒙特卡洛树搜索等技术。
- [OpenAI] [OpenAI o1-mini Advancing cost-efficient reasoning](https://openai.com/index/openai-o1-mini-advancing-cost-efficient-reasoning)
- 概述：介绍了o1 mini模型在推理成本和效率方面的改进，在保持高推理性能的同时，显著降低了计算和运行成本。
- [OpenAI] [Finding GPT-4’s mistakes with GPT-4](https://openai.com/index/finding-gpt4s-mistakes-with-gpt-4/)
- 概述：讨论了如何利用GPT-4模型自身来发现和修正生成的错误。文章中提到的“自我审查方法”通过双重评估提高了错误检测的准确性，从而让模型输出的内容变得更加可靠。（文章发表时，已有OpenAI超级对齐团队成员离职，因此也被称为团队的“遗作”）
- [Tibor Blaho] [Summary of what we have learned during AMA hour with the OpenAI o1 team](https://twitter-thread.com/t/1834686946846597281)
- 概述：这篇博客总结了OpenAI团队在AMA（问答环节）中分享的关于o1模型的主要内容和特性。
其中包括：模型的推理范式以及规模和性能、输入token上下文和模型能力、CoT（思维链）推理、API和使用限制、定价、微调和扩展等内容。
- [Nathan Lambert] [OpenAI’s Strawberry, LM self-talk, inference scaling laws, and spending more on inference](https://www.interconnects.ai/p/openai-strawberry-and-inference-scaling-laws)
- 概述：文章探讨了OpenAI的新活“Strawberry”以及推理扩展定律，强调了推理计算在提升AI能力方面的重要性。而相较于单纯扩大模型规模，作者认为增加推理计算的投入能更有效地提高模型性能。（具有前瞻性的一篇博客，文章发布的时候o1还没发布）
- [Nathan Lambert] [Reverse engineering OpenAI’s o1](https://www.interconnects.ai/p/reverse-engineering-openai-o1)
- 概述：文章详细讲了OpenAI的o1模型，重点在于它的推理能力。o1通过生成复杂的思维链来处理复杂任务，比以前的模型表现更出色。还讨论了o1的设计和训练细节，特别是它如何通过优化数据处理和算法来提高推理效率。同时指出，相比单纯增加模型规模，提升推理计算投入对提升模型性能更有效。
- [Andreas Stuhlmüller, jungofthewon] [Supervise Process, not Outcomes](https://www.alignmentforum.org/posts/pYcFPMBtQveAjcSfH/supervise-process-not-outcomes)
- 

## Talks
- [Noam Brown] [Parables on the Power of Planning in AI: From Poker to Diplomacy](https://www.youtube.com/watch?app=desktop&v=eaAonE58sLU)
- [Hyung Won Chung] [Don't teach. Incentivize.](https://www.youtube.com/watch?v=kYWUEV_e2ss)

## Twitter
- [OpenAI Developers] [We’re hosting an AMA for developers from 10–11 AM PT today.](https://x.com/OpenAIDevs/status/1834608585151594537)
- <img src="https://github.com/user-attachments/assets/4670514c-e6fa-474f-abea-c3f6ad01e41a" width="300px">
- <img src="https://github.com/user-attachments/assets/b390ccea-9773-4a96-ba02-40d917473402" width="300px">
- <img src="https://github.com/user-attachments/assets/aa0678fa-28eb-4b2a-a6ff-c0d123568f22" width="300px">
- <img src="https://github.com/user-attachments/assets/88896f70-017d-4520-ac56-370a023cfe45" width="300px">
- <img src="https://github.com/user-attachments/assets/fbbf78e4-d34c-4b7b-8163-f8c7288f56a6" width="300px">
- <img src="https://github.com/user-attachments/assets/cb1cc1e6-35d4-4567-891a-4e5aca8fa175" width="300px">
- <img src="https://github.com/user-attachments/assets/d3fd109b-0c97-4a94-931e-919b3b2f75f4" width="300px">


## Papers

```
format:
- [title](paper link) [links]
  - author1, author2, and author3...
  - publisher
  - code
  - experimental environments and datasets
```
### Relevant Paper from OpenAI o1 [contributors](https://openai.com/openai-o1-contributions/)
- [Training Verifiers to Solve Math Word Problems](https://arxiv.org/abs/2110.14168)
- 概述：发布于2021年10月，文中指出虽然当前的先进语言模型在很多任务上表现很强，但它们在解决复杂的数学题时仍然遇到困难。为了解决这个问题，作者创建了一个叫GSM8K的数据集，其中包含8500个不同的小学数学题。研究发现，即使是大规模的Transformer模型在这些题目上也表现不佳。为了提升表现，作者建议使用一个验证器来检查模型答案的准确性。具体做法是让模型生成多个答案，然后选择验证器评分最高的答案。而这种方法显著提高了模型在GSM8K数据集上的表现，比传统的调整方法效果更好。
  - Karl Cobbe, Vineet Kosaraju, Mohammad Bavarian, Mark Chen, Heewoo Jun, Lukasz Kaiser, Matthias Plappert, Jerry Tworek, Jacob Hilton, Reiichiro Nakano, Christopher Hesse, John Schulman
- [Generative Language Modeling for Automated Theorem Proving](https://arxiv.org/abs/2009.03393)
- 概述：发布于2020年9月，探讨了基于Transformer的语言模型如何在自动定理证明中发挥作用。研究的核心问题是，自动定理证明器在生成原创数学术语方面比不上人类，而这可能通过语言模型的生成能力得到解决。作者介绍了一种叫做GPT-f的自动证明工具，用于Metamath形式化语言，并分析了它的效果。GPT-f成功发现了一些新短证明，这些证明被Metamath主要库接受，这是深度学习系统首次为形式数学社区提供并被采纳的证明。
  - Stanislas Polu, Ilya Sutskever
- [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)
- 概述：发布于2022年1月，文章讨论了如何通过生成一系列中间推理步骤（思维链）来大幅提升大型语言模型的复杂推理能力。作者提出了一种叫做“思维链提示”的方法，具体做法是在提示中给出一些思维链的示例，帮助模型进行更深入的推理。最终实验结果显示，它在三个大型语言模型上都显著提高了它们在算术、常识和符号推理任务中的表现。
  - Jason Wei, Xuezhi Wang, Dale Schuurmans, Maarten Bosma, Brian Ichter, Fei Xia, Ed Chi, Quoc Le, Denny Zhou
- [Let's Verify Step by Step](https://arxiv.org/abs/2305.20050)
- 概述：发布于2023年5月，文章讨论了大型语言模型在复杂多步推理任务中的表现。作者比较了两种训练方法：一种只关注最终结果，另一种关注每一步推理。结果显示，关注每一步推理的方法更有效，能在MATH数据集上提高到78%的成功率。文中还强调了主动学习在提升训练效果中的重要性，并发布了一个包含80万个步骤级反馈的PRM800K数据集，用于训练最佳模型。
  - Hunter Lightman, Vineet Kosaraju, Yura Burda, Harri Edwards, Bowen Baker, Teddy Lee, Jan Leike, John Schulman, Ilya Sutskever, Karl Cobbe
- [LLM Critics Help Catch LLM Bugs](https://arxiv.org/abs/2407.00215)
- 概述：发布于2024年6月，文中介绍了用“批评者”（CriticGPT）模型来提升机器学习模型输出的评估。这些批评者模型能更有效地发现代码中的错误，甚至能找到人类可能忽略的问题。尽管这些模型有时会出错，但与人类结合使用可以减少误导，同时提高错误检测的效率。
  - Nat McAleese, Rai Michael Pokorny, Juan Felipe Ceron Uribe, Evgenia Nitishinskaya, Maja Trebacz, Jan Leike
- [Self-critiquing models for assisting human evaluators](https://arxiv.org/pdf/2206.05802)
- 概述：发布于2022年6月，文中介绍了一种方法，通过微调大型语言模型，让它们生成批评性评论，从而帮助找出摘要中的问题。研究发现，这些评论可以有效识别摘要中的错误，包括有意误导的信息。大模型在生成有用评论和自我改进方面表现更好。同时论文还提出了一个框架来评估模型的批评、生成和辨别能力，并指出即使是大型模型也可能有遗漏的知识。研究展示了如何用AI辅助人类改进机器学习系统，并公开了相关数据和样本。
  - William Saunders, Catherine Yeh, Jeff Wu, Steven Bills, Long Ouyang, Jonathan Ward, Jan Leike
- [Scalable Online Planning via Reinforcement Learning Fine-Tuning](https://arxiv.org/abs/2109.15316)
- 概述：文章介绍了一种新方法来改进图神经网络（GNN）的训练，特别是针对“图卷积”操作中的效率问题。作者提出了一种名为“FastGCN”的算法，旨在提高图神经网络的计算速度和缩放能力。通过在训练过程中进行近似和优化，这种方法能够处理更大规模的图数据，从而在图数据分析任务中取得更好的性能。
  - Arnaud Fickinger, Hengyuan Hu, Brandon Amos, Stuart Russell, Noam Brown.

### 2024
- [Planning In Natural Language Improves LLM Search For Code Generation](https://arxiv.org/abs/2409.03733)
  - Evan Wang, Federico Cassano, Catherine Wu, Yunfeng Bai, Will Song, Vaskar Nath, Ziwen Han, Sean Hendryx, Summer Yue, Hugh Zhang
- [Training Language Models to Self-Correct via Reinforcement Learning](https://arxiv.org/abs/2409.12917)
  - Aviral Kumar, Vincent Zhuang, Rishabh Agarwal, Yi Su, John D Co-Reyes, Avi Singh, Kate Baumli, Shariq Iqbal, Colton Bishop, Rebecca Roelofs, Lei M Zhang, Kay McKinney, Disha Shrivastava, Cosmin Paduraru, George Tucker, Doina Precup, Feryal Behbahani, Aleksandra Faust
- [To CoT or not to CoT? Chain-of-thought helps mainly on math and symbolic reasoning](https://arxiv.org/abs/2409.12183)
  - Zayne Sprague, Fangcong Yin, Juan Diego Rodriguez, Dongwei Jiang, Manya Wadhwa, Prasann Singhal, Xinyu Zhao, Xi Ye, Kyle Mahowald, Greg Durrett
- [An Empirical Analysis of Compute-Optimal Inference for Problem-Solving with Language Models](https://arxiv.org/abs/2408.00724)
  - Yangzhen Wu, Zhiqing Sun, Shanda Li, Sean Welleck, Yiming Yang
- [Smaller, Weaker, Yet Better: Training LLM Reasoners via Compute-Optimal Sampling](https://www.arxiv.org/abs/2408.16737)
  - Hritik Bansal, Arian Hosseini, Rishabh Agarwal, Vinh Q. Tran, Mehran Kazemi
- [Scaling LLM Test-Time Compute Optimally can be More Effective than Scaling Model Parameters](https://arxiv.org/abs/2408.03314)
  - Charlie Snell, Jaehoon Lee, Kelvin Xu, Aviral Kumar
- [Generative Verifiers: Reward Modeling as Next-Token Prediction](https://arxiv.org/abs/2408.15240)
  - Lunjun Zhang, Arian Hosseini, Hritik Bansal, Mehran Kazemi, Aviral Kumar, Rishabh Agarwal
- [Mutual Reasoning Makes Smaller LLMs Stronger Problem-Solvers](https://arxiv.org/abs/2408.06195)
  - Zhenting Qi, Mingyuan Ma, Jiahang Xu, Li Lyna Zhang, Fan Yang, Mao Yang
- [Large Language Monkeys: Scaling Inference Compute with Repeated Sampling](https://arxiv.org/abs/2407.21787)
  - Bradley Brown, Jordan Juravsky, Ryan Ehrlich, Ronald Clark, Quoc V. Le, Christopher Ré, Azalia Mirhoseini
- [Improve Mathematical Reasoning in Language Models by Automated Process Supervision](https://arxiv.org/abs/2406.06592)
  - Liangchen Luo, Yinxiao Liu, Rosanne Liu, Samrat Phatale, Harsh Lara, Yunxuan Li, Lei Shu, Yun Zhu, Lei Meng, Jiao Sun, Abhinav Rastogi
- [Q*: Improving Multi-step Reasoning for LLMs with Deliberative Planning](https://arxiv.org/abs/2406.14283)
  - Chaojie Wang, Yanchen Deng, Zhiyi Lyu, Liang Zeng, Jujie He, Shuicheng Yan, Bo An
- [Accessing GPT-4 level Mathematical Olympiad Solutions via Monte Carlo Tree Self-refine with LLaMa-3 8B](https://arxiv.org/abs/2406.07394)
  - Di Zhang, Xiaoshui Huang, Dongzhan Zhou, Yuqiang Li, Wanli Ouyang
- [Self-Rewarding Language Models](https://arxiv.org/abs/2401.10020)
  - Weizhe Yuan, Richard Yuanzhe Pang, Kyunghyun Cho, Xian Li, Sainbayar Sukhbaatar, Jing Xu, Jason Weston
- [Uncertainty of Thoughts: Uncertainty-Aware Planning Enhances Information Seeking in Large Language Models](https://arxiv.org/abs/2402.03271)
  - Zhiyuan Hu, Chumin Liu, Xidong Feng, Yilun Zhao, See-Kiong Ng, Anh Tuan Luu, Junxian He, Pang Wei Koh, Bryan Hooi
- [Quiet-STaR: Language Models Can Teach Themselves to Think Before Speaking](https://arxiv.org/abs/2403.09629)
  - Eric Zelikman, Georges Harik, Yijia Shao, Varuna Jayasiri, Nick Haber, Noah D. Goodman
  - https://github.com/ezelikman/quiet-star
- [Advancing LLM Reasoning Generalists with Preference Trees](https://arxiv.org/abs/2404.02078)
  - Lifan Yuan, Ganqu Cui, Hanbin Wang, Ning Ding, Xingyao Wang, Jia Deng, Boji Shan et al.
- [Toward Self-Improvement of LLMs via Imagination, Searching, and Criticizing](https://arxiv.org/abs/2404.12253)
  - Ye Tian, Baolin Peng, Linfeng Song, Lifeng Jin, Dian Yu, Haitao Mi, and Dong Yu.
- [AlphaMath Almost Zero: Process Supervision Without Process](https://arxiv.org/abs/2405.03553)
  - Guoxin Chen, Minpeng Liao, Chengxi Li, Kai Fan.
- [ReST-MCTS*: LLM Self-Training via Process Reward Guided Tree Search](https://arxiv.org/abs/2406.03816)
  - Dan Zhang, Sining Zhoubian, Yisong Yue, Yuxiao Dong, and Jie Tang.
- [MindStar: Enhancing Math Reasoning in Pre-trained LLMs at Inference Time](https://arxiv.org/abs/2405.16265)
  - Jikun Kang, Xin Zhe Li, Xi Chen, Amirreza Kazemi, Qianyi Sun, Boxing Chen, Dong Li, Xu He, Quan He, Feng Wen, Jianye Hao, Jun Yao.
- [Monte Carlo Tree Search Boosts Reasoning via Iterative Preference Learning](https://arxiv.org/abs/2405.00451)
  - Yuxi Xie, Anirudh Goyal, Wenyue Zheng, Min-Yen Kan, Timothy P. Lillicrap, Kenji Kawaguchi, Michael Shieh.
- [Chain of Thought Empowers Transformers to Solve Inherently Serial Problems](https://arxiv.org/abs/2402.12875)
  - Zhiyuan Li, Hong Liu, Denny Zhou, Tengyu Ma.
- [ReFT: Reasoning with Reinforced Fine-Tuning](https://arxiv.org/abs/2401.08967)
  - Trung Quoc Luong, Xinbo Zhang, Zhanming Jie, Peng Sun, Xiaoran Jin, Hang Li
- [Chain-of-Thought Reasoning Without Prompting](https://arxiv.org/pdf/2402.10200)
  - Xuezhi Wang, Denny Zhou
- [Chain of Preference Optimization: Improving Chain-of-Thought Reasoning in LLMs](https://arxiv.org/abs/2406.09136)
  - Xuan Zhang, Chao Du, Tianyu Pang, Qian Liu, Wei Gao, Min Lin

### 2023
- [Training Chain-of-Thought via Latent-Variable Inference](https://arxiv.org/pdf/2312.02179)
  - Du Phan, Matthew D. Hoffman, David Dohan, Sholto Douglas, Tuan Anh Le, Aaron Parisi, Pavel Sountsov, Charles Sutton, Sharad Vikram, Rif A. Saurous
- [Alphazero-like Tree-Search can Guide Large Language Model Decoding and Training](https://arxiv.org/abs/2309.17179)
  - Xidong Feng, Ziyu Wan, Muning Wen, Stephen Marcus McAleer, Ying Wen, Weinan Zhang, Jun Wang
- [Reasoning with Language Model is Planning with World Model](https://arxiv.org/abs/2305.14992)
  - Shibo Hao, Yi Gu, Haodi Ma, Joshua Jiahua Hong, Zhen Wang, Daisy Zhe Wang, Zhiting Hu
- [Don’t throw away your value model! Generating more preferable text with Value-Guided Monte-Carlo Tree Search decoding](https://arxiv.org/abs/2309.15028)
  - Liu, Jiacheng, Andrew Cohen, Ramakanth Pasunuru, Yejin Choi, Hannaneh Hajishirzi, and Asli Celikyilmaz.
- [Certified reasoning with language models](https://arxiv.org/pdf/2306.04031)
  - Gabriel Poesia, Kanishk Gandhi, Eric Zelikman, Noah D. Goodman

### 2022
- [Chain of Thought Imitation with Procedure Cloning](https://arxiv.org/abs/2205.10816)
  - Mengjiao Yang, Dale Schuurmans, Pieter Abbeel, Ofir Nachum.
- [STaR: Bootstrapping Reasoning With Reasoning](https://arxiv.org/abs/2203.14465)
  - Eric Zelikman, Yuhuai Wu, Jesse Mu, Noah D. Goodman
- [Solving math word problems with processand outcome-based feedback](https://arxiv.org/abs/2211.14275)
  - Jonathan Uesato, Nate Kushman, Ramana Kumar, Francis Song, Noah Siegel, Lisa Wang, Antonia Creswell, Geoffrey Irving, Irina Higgins

### 2021
- [Scaling Scaling Laws with Board Games](http://arxiv.org/abs/2104.03113)
  - Andy L. Jones.
- [Show Your Work: Scratchpads for Intermediate Computation with Language Models](https://arxiv.org/pdf/2112.00114)
  - Maxwell Nye, Anders Johan Andreassen, Guy Gur-Ari, Henryk Michalewski, Jacob Austin, David Bieber, David Dohan, Aitor Lewkowycz, Maarten Bosma, David Luan, Charles Sutton, Augustus Odena

### 2017
- [Mastering Chess and Shogi by Self-Play with a General Reinforcement Learning Algorithm](https://arxiv.org/abs/1712.01815v1)
  - David Silver, Thomas Hubert, Julian Schrittwieser, Ioannis Antonoglou, Matthew Lai, Arthur Guez, Marc Lanctot, Laurent Sifre, Dharshan Kumaran, Thore Graepel, Timothy Lillicrap, Karen Simonyan, Demis Hassabis.

## Projects
- [Maitrix.org] [LLM Reasoners](https://github.com/maitrix-org/llm-reasoners)
- [bklieger-groq] [g1: Using Llama-3.1 70b on Groq to create o1-like reasoning chains](https://github.com/bklieger-groq/g1)
- [toyberry] [Toyberry: A end to end tiny implementation of OpenAI's o1 reasoning system using MCTS and LLM as backend](https://github.com/ack-sec/toyberry)

## Evaluation
- ~~[AryanDLuffy] [Codeforces - O1-mini benchmark](https://codeforces.com/blog/entry/133962)~~
- [Dominater069] [Codeforces - Analyzing how good O1-Mini actually is](https://codeforces.com/blog/entry/133887)
