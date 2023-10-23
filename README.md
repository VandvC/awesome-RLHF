# Awesome RLHF (RL with Human Feedback)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ![visitors](https://visitor-badge.glitch.me/badge?page_id=opendilab/awesome-RLHF) ![GitHub stars](https://img.shields.io/github/stars/opendilab/awesome-RLHF?color=yellow) ![GitHub forks](https://img.shields.io/github/forks/opendilab/awesome-RLHF?color=9cf) [![GitHub license](https://img.shields.io/github/license/opendilab/awesome-RLHF)](https://github.com/opendilab/awesome-RLHF/blob/main/LICENSE)

This is a collection of research papers for **Reinforcement Learning with Human Feedback** (RLHF).
And the repository will be continuously updated to track the frontier of RLHF.

Welcome to follow and star!


## Table of Contents

- [Awesome RLHF (RL with Human Feedback)](#awesome-rlhf-rl-with-human-feedback)
  - [Table of Contents](#table-of-contents)
  - [Overview of RLHF](#overview-of-rlhf)
    - [Detailed Explanation](#detailed-explanation)
  - [Papers](#papers)
    - [2023](#2023)
    - [2022](#2022)
    - [2021](#2021)
    - [2020 and before](#2020-and-before)
  - [Codebases](#codebases)
  - [Dataset](#dataset)
  - [Blogs](#blogs)
  - [Other Language Support](#other-language-support)
  - [Contributing](#contributing)
  - [License](#license)

## Overview of RLHF

The idea of RLHF is to use methods from reinforcement learning to directly optimize a language model with human feedback. RLHF has enabled language models to begin to align a model trained on a general corpus of text data to that of complex human values.

- RLHF for Large Language Model (LLM)

![image info](./overview_chatgpt.png)

- RLHF for Video Game (e.g. Atari)

![image info](./overview_video_game.png)

### Detailed Explanation 

**(The following section was automatically generated by ChatGPT)**

RLHF typically refers to "Reinforcement Learning with Human Feedback". Reinforcement Learning (RL) is a type of machine learning that involves training an agent to make decisions based on feedback from its environment. In RLHF, the agent also receives feedback from humans in the form of ratings or evaluations of its actions, which can help it learn more quickly and accurately.

RLHF is an active research area in artificial intelligence, with applications in fields such as robotics, gaming, and personalized recommendation systems. It seeks to address the challenges of RL in scenarios where the agent has limited access to feedback from the environment and requires human input to improve its performance.

Reinforcement Learning with Human Feedback (RLHF) is a rapidly developing area of research in artificial intelligence, and there are several advanced techniques that have been developed to improve the performance of RLHF systems. Here are some examples:

- `Inverse Reinforcement Learning (IRL)`: IRL is a technique that allows the agent to learn a reward function from human feedback, rather than relying on pre-defined reward functions. This makes it possible for the agent to learn from more complex feedback signals, such as demonstrations of desired behavior.

- `Apprenticeship Learning`: Apprenticeship learning is a technique that combines IRL with supervised learning to enable the agent to learn from both human feedback and expert demonstrations. This can help the agent learn more quickly and effectively, as it is able to learn from both positive and negative feedback.

- `Interactive Machine Learning (IML)`: IML is a technique that involves active interaction between the agent and the human expert, allowing the expert to provide feedback on the agent's actions in real-time. This can help the agent learn more quickly and efficiently, as it can receive feedback on its actions at each step of the learning process.

- `Human-in-the-Loop Reinforcement Learning (HITLRL)`: HITLRL is a technique that involves integrating human feedback into the RL process at multiple levels, such as reward shaping, action selection, and policy optimization. This can help to improve the efficiency and effectiveness of the RLHF system by taking advantage of the strengths of both humans and machines.

Here are some examples of Reinforcement Learning with Human Feedback (RLHF):

- `Game Playing`: In game playing, human feedback can help the agent learn strategies and tactics that are effective in different game scenarios. For example, in the popular game of Go, human experts can provide feedback to the agent on its moves, helping it improve its gameplay and decision-making.

- `Personalized Recommendation Systems`: In recommendation systems, human feedback can help the agent learn the preferences of individual users, making it possible to provide personalized recommendations. For example, the agent could use feedback from users on recommended products to learn which features are most important to them.

- `Robotics`: In robotics, human feedback can help the agent learn how to interact with the physical environment in a safe and efficient manner. For example, a robot could learn to navigate a new environment more quickly with feedback from a human operator on the best path to take or which objects to avoid.

- `Education`: In education, human feedback can help the agent learn how to teach students more effectively. For example, an AI-based tutor could use feedback from teachers on which teaching strategies work best with different students, helping to personalize the learning experience.

## Papers

```
format:
- [title](paper link) [links]
  - author1, author2, and author3...
  - publisher
  - keyword
  - code
  - experiment environments and datasets
```

### 2023
- [AlignDiff: Aligning Diverse Human Preferences via Behavior-Customisable Diffusion Model](https://arxiv.org/abs/2310.02054)
  - Zibin Dong, Yifu Yuan, Jianye Hao, Fei Ni, Yao Mu, Yan Zheng, Yujing Hu, Tangjie Lv, Changjie Fan, Zhipeng Hu
  - Keyword: RLHF, Alignment, Diffusion model

- [Eureka: Human-Level Reward Design via Coding Large Language Models](https://arxiv.org/abs/2310.12931)
  - Yecheng Jason Ma, William Liang, Guanzhi Wang, De-An Huang, Osbert Bastani, Dinesh Jayaraman, Yuke Zhu, Linxi Fan, Anima Anandkumar
  - Keyword: LLM based, reward functions design

- [Safe RLHF: Safe Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2310.12773)
  - Josef Dai, Xuehai Pan, Ruiyang Sun, Jiaming Ji, Xinbo Xu, Mickel Liu, Yizhou Wang, Yaodong Yang
  - Keyword: Sale RL, LLM fine-ture

- [Quality Diversity through Human Feedback](https://arxiv.org/abs/2310.12103)
  - Li Ding, Jenny Zhang, Jeff Clune, Lee Spector, Joel Lehman
  - Keyword: Quality Diversity, Diffusion model

- [ReMax: A Simple, Effective, and Efficient Reinforcement Learning Method for Aligning Large Language Models](https://arxiv.org/abs/2310.10505)
  - Ziniu Li, Tian Xu, Yushun Zhang, Yang Yu, Ruoyu Sun, Zhi-Quan Luo
  - Keyword: computational efficiency, variance-reduction technique

- [Tuning computer vision models with task rewards](https://arxiv.org/abs/2302.08242.pdf)
  - André Susano Pinto, Alexander Kolesnikov, Yuge Shi, Lucas Beyer, Xiaohua Zhai
  - Keyword: Reward tuning in Computer Vision

- [The Wisdom of Hindsight Makes Language Models Better Instruction Followers](https://arxiv.org/pdf/2302.05206.pdf)
  - Tianjun Zhang, Fangchen Liu, Justin Wong, Pieter Abbeel, Joseph E. Gonzalez
  - Keyword: Hindsight Instruction Relabeling, RLHF System, No Value Network Required
  - Code: [official](https://github.com/tianjunz/HIR)

- [Language Instructed Reinforcement Learning for Human-AI Coordination](https://arxiv.org/pdf/2304.07297.pdf)
  - Hengyuan Hu, Dorsa Sadigh
  - Keyword: Human-AI coordination, Human preference alignment, Instruction conditioned RL

- [Aligning Language Models with Offline Reinforcement Learning from Human Feedback](https://arxiv.org/pdf/2308.12050.pdf)
  - Jian Hu, Li Tao, June Yang, Chandler Zhou
  - Keyword: Decision Transformer-based Alignment, Offline Reinforcement Learning, RLHF System

- [Preference Ranking Optimization for Human Alignment](https://arxiv.org/pdf/2306.17492.pdf)
  - Feifan Song, Bowen Yu, Minghao Li, Haiyang Yu, Fei Huang, Yongbin Li and Houfeng Wang
  - Keyword: Supervised Human Preference Alignment, Preference Ranking Extension
  - Code: [official](https://github.com/AlibabaResearch/DAMO-ConvAI/tree/main/PRO)

- [Bridging the Gap: A Survey on Integrating (Human) Feedback for Natural Language Generation](https://arxiv.org/abs/2305.00955)
  - Patrick Fernandes, Aman Madaan, Emmy Liu, António Farinhas, Pedro Henrique Martins, Amanda Bertsch, José G. C. de Souza, Shuyan Zhou, Tongshuang Wu, Graham Neubig, André F. T. Martins
  - Keyword: Natural Language Generation, Human Feedback Integration, Feedback Formalization and Taxonomy, AI Feedback and Principles-Based Judgments

- [GPT-4 Technical Report](https://cdn.openai.com/papers/gpt-4.pdf)
  - OpenAI
  - Keyword: A large-scale, multimodal model, Transformerbased model, Fine-tuned used RLHF
  - Code: [official](https://github.com/openai/evals)
  - Dataset: [DROP](https://allenai.org/data/drop), [WinoGrande](https://winogrande.allenai.org/), [HellaSwag](https://rowanzellers.com/hellaswag/), [ARC](https://allenai.org/data/arc), [HumanEval](https://github.com/openai/human-eval), [GSM8K](https://paperswithcode.com/dataset/gsm8k), [MMLU](https://paperswithcode.com/dataset/mmlu), [TruthfulQA](https://github.com/sylinrl/TruthfulQA)

- [RAFT: Reward rAnked FineTuning for Generative Foundation Model Alignment](https://arxiv.org/pdf/2304.06767.pdf)
  - Hanze Dong, Wei Xiong, Deepanshu Goyal, Rui Pan, Shizhe Diao, Jipeng Zhang, Kashun Shum, Tong Zhang
  - Keyword: Alternative to PPO, ChatGPT, Diffusion Model
  - Code: [official](https://github.com/OptimalScale/LMFlow)
  
- [RRHF: Rank Responses to Align Language Models with Human Feedback without tears](https://arxiv.org/pdf/2304.05302v1.pdf)
  - Zheng Yuan, Hongyi Yuan, Chuanqi Tan, Wei Wang, Songfang Huang, Fei Huang
  - Keyword: New paradigm for RLHF
  - Code: [official](https://github.com/GanjinZero/RRHF)

- [Few-shot Preference Learning for Human-in-the-Loop RL](https://openreview.net/pdf?id=IKC5TfXLuW0)
  - Joey Hejna, Dorsa Sadigh
  - Keyword: Preference Learning, Interactive Learning, Multi-task Learning, Expanding the pool of available data by viewing human-in-the-loop RL
  - Code: [official](https://github.com/jhejna/few-shot-preference-rl)

- [Better Aligning Text-to-Image Models with Human Preference](https://arxiv.org/abs/2303.14420)
  - Xiaoshi Wu, Keqiang Sun, Feng Zhu, Rui Zhao, Hongsheng Li
  - Keyword: Diffusion Model, Text-to-Image, Aesthetic
  - Code: [official](https://github.com/tgxs002/align_sd)

- [ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation](https://arxiv.org/pdf/2304.05977v2.pdf)
  - Jiazheng Xu, Xiao Liu, Yuchen Wu, Yuxuan Tong, Qinkai Li, Ming Ding, Jie Tang, Yuxiao Dong
  - Keyword: General-purpose text-to-Image human preference RM, Evaluating Text-to-Image Generative Models
  - Code: [official](https://github.com/THUDM/ImageReward)
  - Dataset: [COCO](https://cocodataset.org/#home), [DiffusionDB](https://poloclub.github.io/diffusiondb/)

- [Aligning Text-to-Image Models using Human Feedback](https://arxiv.org/pdf/2302.12192.pdf)
  - Kimin Lee, Hao liu, MoonKyung Ryu, Olivia Watkins, Yuqing Du, Craig Boutilier, Pieter Abbeel, Mohammad Ghavamzadeh, Shixiang Shane Gu
  - Keyword: Text-to-Image, Stable diffusion model, Reward function that predicts human feedback

- [Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models](https://arxiv.org/pdf/2303.04671.pdf)
  - Chenfei Wu, Shengming Yin, Weizhen Qi, Xiaodong Wang, Zecheng Tang, Nan Duan
  - Keyword: Visual Foundation Models, Visual ChatGPT 
  - Code: [official](https://github.com/microsoft/visual-chatgpt)

- [Pretraining Language Models with Human Preferences](https://arxiv.org/abs/2302.08582) (PHF)
  - Tomasz Korbak, Kejian Shi, Angelica Chen, Rasika Bhalerao, Christopher L. Buckley, Jason Phang, Samuel R. Bowman, Ethan Perez
  - Keyword: Pretraining, offline RL, Decision transformer
  - Code: [official](https://github.com/tomekkorbak/pretraining-with-human-feedback)

- [Aligning Language Models with Preferences through f-divergence Minimization](https://arxiv.org/abs/2302.08215) (f-DPG)
  - Dongyoung Go, Tomasz Korbak, Germán Kruszewski, Jos Rozen, Nahyeon Ryu, Marc Dymetman
  - Keyword: f-divergence, RL with KL penalties

- [Principled Reinforcement Learning with Human Feedback from Pairwise or K-wise Comparisons](https://arxiv.org/pdf/2301.11270.pdf)
  - Banghua Zhu, Jiantao Jiao, Michael I. Jordan
  - Keyword: Pessimistic MLE, Max-entropy IRL

- [The Capacity for Moral Self-Correction in Large Language Models](https://arxiv.org/pdf/2302.07459.pdf)
  - Anthropic
  - Keyword: Improve moral self-correction capability by increasing RLHF training
  - Dataset; [BBQ](https://github.com/nyu-mll/BBQ)

### 2022

- [Is Reinforcement Learning (Not) for Natural Language Processing?: Benchmarks, Baselines, and Building Blocks for Natural Language Policy Optimization](https://arxiv.org/abs/2210.01241) (NLPO)
  - Rajkumar Ramamurthy, Prithviraj Ammanabrolu, Kianté,Brantley, Jack Hessel, Rafet Sifa, Christian Bauckhage, Hannaneh Hajishirzi, Yejin Choi
  - Keyword: Optimizing language generators with RL, Benchmark,  Performant RL algorithm
  - Code: [official](https://github.com/allenai/RL4LMs)
  - Dataset: [IMDB](https://www.imdb.com/interfaces/), [CommonGen](https://inklab.usc.edu/CommonGen/), [CNN Daily Mail](https://github.com/abisee/cnn-dailymail), [ToTTo](https://github.com/google-research-datasets/ToTTo), [WMT-16 (en-de)](https://www.statmt.org/wmt16/it-translation-task.html),[NarrativeQA](https://github.com/deepmind/narrativeqa), [DailyDialog](http://yanran.li/dailydialog)
- [Scaling Laws for Reward Model Overoptimization](https://arxiv.org/abs/2210.10760)
  - Leo Gao, John Schulman, Jacob Hilton
  - Keyword: Gold reward model train proxy reward model, Dataset size, Policy parameter size, BoN, PPO
- [Improving alignment of dialogue agents via targeted human judgements](https://arxiv.org/abs/2209.14375) (Sparrow)
  - Amelia Glaese, Nat McAleese, Maja Trębacz, et al.
  - Keyword: Information-seeking dialogue agent, Break down the good dialogue into natural language rules, DPC, Interact with the model to elicit violation of a specific rule (Adversarial Probing)
  - Dataset: [Natural Questions](https://ai.google.com/research/NaturalQuestions), [ELI5](https://facebookresearch.github.io/ELI5/), [QuALITY](https://github.com/nyu-mll/quality), [TriviaQA](http://nlp.cs.washington.edu/triviaqa/), [WinoBias](https://github.com/uclanlp/corefBias/tree/master/WinoBias/wino), [BBQ](https://github.com/nyu-mll/BBQ)
- [Red Teaming Language Models to Reduce Harms: Methods, Scaling Behaviors, and Lessons Learned](https://arxiv.org/abs/2209.07858)
  - Deep Ganguli, Liane Lovitt, Jackson Kernion, et al.
  - Keyword: Red team language model, Investigate scaling behaviors, Read teaming Dataset
  - Code: [official](https://github.com/anthropics/hh-rlhf)
- [Dynamic Planning in Open-Ended Dialogue using Reinforcement Learning](https://arxiv.org/abs/2208.02294)
  - Deborah Cohen, Moonkyung Ryu, Yinlam Chow, Orgad Keller, Ido Greenberg, Avinatan Hassidim, Michael Fink, Yossi Matias, Idan Szpektor, Craig Boutilier, Gal Elidan
  - Keyword: Real-time, Open-ended dialogue system, Pairs the succinct embedding of the conversation state by language models, CAQL, CQL, [BERT](https://github.com/google-research/bert)
- [Quark: Controllable Text Generation with Reinforced Unlearning](https://arxiv.org/abs/2205.13636)
  - Ximing Lu, Sean Welleck, Jack Hessel, Liwei Jiang, Lianhui Qin, Peter West, Prithviraj Ammanabrolu, Yejin Choi
  - Keyword: Fine-tuning the language model on signals of what not to do, Decision Transformer, LLM tuning with PPO
  - Code: [official](https://github.com/gximinglu/quark)
  - Dataset: [WRITINGPROMPTS](https://www.kaggle.com/datasets/ratthachat/writing-prompts), [SST-2](https://huggingface.co/distilbert-base-uncased-finetuned-sst-2-english), [WIKITEXT-103](https://blog.salesforceairesearch.com/the-wikitext-long-term-dependency-language-modeling-dataset/)
- [Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback](https://arxiv.org/abs/2204.05862)
  - Yuntao Bai, Andy Jones, Kamal Ndousse, et al.
  - Keyword: Harmless assistants, Online mode, Robustness of RLHF training, OOD detection.
  - Code: [official](https://github.com/anthropics/hh-rlhf)
  - Dataset: [TriviaQA](http://nlp.cs.washington.edu/triviaqa/), [HellaSwag](https://rowanzellers.com/hellaswag/), [ARC](https://allenai.org/data/arc), [OpenBookQA](https://allenai.org/data/open-book-qa), [LAMBADA](https://zenodo.org/record/2630551#.Y_KLJ-yZNhF), [HumanEval](https://github.com/openai/human-eval), [MMLU](https://github.com/hendrycks/test), [TruthfulQA](https://github.com/sylinrl/TruthfulQA)
- [Teaching language models to support answers with verified quotes](https://arxiv.org/abs/2203.11147) (GopherCite)
  - Jacob Menick, Maja Trebacz, Vladimir Mikulik, John Aslanides, Francis Song, Martin Chadwick, Mia Glaese, Susannah Young, Lucy Campbell-Gillingham, Geoffrey Irving, Nat McAleese
  - Keyword: Generate answers which citing specific evidence, Abstain from answering when unsure
  - Dataset: [Natural Questions](https://ai.google.com/research/NaturalQuestions), [ELI5](https://facebookresearch.github.io/ELI5/), [QuALITY](https://github.com/nyu-mll/quality), [TruthfulQA](https://github.com/sylinrl/TruthfulQA)
- [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155) (InstructGPT)
  - Long Ouyang, Jeff Wu, Xu Jiang, et al.
  - Keyword: Large Language Model, Align Language Model with Human Intent
  - Code: [official](https://github.com/openai/following-instructions-human-feedback)
  - Dataset: [TruthfulQA](https://github.com/sylinrl/TruthfulQA), [RealToxicityPrompts](https://allenai.org/data/real-toxicity-prompts)
- [Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/pdf/2212.08073.pdf)
  - Yuntao Bai, Saurav Kadavath, Sandipan Kundu, Amanda Askell, Jackson Kernion, et al.
  - Keyword: RL from AI feedback(RLAIF), Training a harmless AI assistant through selfimprovement, Chain-of-thought style, Control AI behavior more precisely
  - Code: [official](https://github.com/anthropics/ConstitutionalHarmlessnessPaper)
- [Discovering Language Model Behaviors with Model-Written Evaluations](https://arxiv.org/abs/2212.09251)
  - Ethan Perez, Sam Ringer, Kamilė Lukošiūtė, Karina Nguyen, Edwin Chen, et al.
  - Keyword: Automatically generate evaluations with LMs, More RLHF makes LMs worse, LM-written evaluations are highquality
  - Code: [official](https://github.com/anthropics/evals)
  - Dataset: [BBQ](https://github.com/nyu-mll/BBQ), [Winogender Schemas](https://github.com/rudinger/winogender-schemas)
- [Non-Markovian Reward Modelling from Trajectory Labels via Interpretable Multiple Instance Learning](https://arxiv.org/abs/2205.15367)
  - Joseph Early, Tom Bewley, Christine Evers, Sarvapali Ramchurn
  - Keyword: Reward Modelling (RLHF), Non-Markovian, Multiple Instance Learning, Interpretability
  - Code: [official](https://github.com/JAEarly/MIL-for-Non-Markovian-Reward-Modelling)

### 2021
- [WebGPT: Browser-assisted question-answering with human feedback](https://arxiv.org/abs/2112.09332) (WebGPT)
  - Reiichiro Nakano, Jacob Hilton, Suchir Balaji, et al.
  - Keyword: Model search the web and provide reference， Imitation learning， BC, long form question
  - Dataset: [ELI5](https://facebookresearch.github.io/ELI5/), [TriviaQA](http://nlp.cs.washington.edu/triviaqa/), [TruthfulQA](https://github.com/sylinrl/TruthfulQA)
- [Recursively Summarizing Books with Human Feedback](https://arxiv.org/abs/2109.10862)
  - Jeff Wu, Long Ouyang, Daniel M. Ziegler, Nisan Stiennon, Ryan Lowe, Jan Leike, Paul Christiano
  - Keyword:  Model trained on small task to assist human evaluate broader task, BC
  - Dataset: [Booksum](https://github.com/salesforce/booksum), [NarrativeQA](https://github.com/deepmind/narrativeqa)
- [Revisiting the Weaknesses of Reinforcement Learning for Neural Machine Translation](https://arxiv.org/abs/2106.08942)
  - Samuel Kiegeland, Julia Kreutzer
  - Keyword:  The success of policy gradient is because of reward rather than the shape of output distribution, Machine Translation, NMT, DOmain Adaption
  - Code: [official](https://github.com/samuki/reinforce-joey)
  - Dataset: [WMT15](https://www.statmt.org/wmt15/index.html), [IWSLT14](https://sites.google.com/site/iwsltevaluation2014/mt-track)

### 2020 and before

- [Learning to summarize from human feedback](https://arxiv.org/abs/2009.01325)
  - Nisan Stiennon, Long Ouyang, Jeff Wu, Daniel M. Ziegler, Ryan Lowe, Chelsea Voss, Alec Radford, Dario Amodei, Paul Christiano
  - Keyword: Care about summary quality, Training loss affect the model behavior, Reward model generalizes to new datasets
  - Code: [official](https://github.com/openai/summarize-from-feedback)
  - Dataset: [TL;DR](https://www.tensorflow.org/datasets/catalog/reddit), [CNN/DM](https://github.com/abisee/cnn-dailymail)
- [Fine-Tuning Language Models from Human Preferences](https://arxiv.org/abs/1909.08593)
  - Daniel M. Ziegler, Nisan Stiennon, Jeffrey Wu, Tom B. Brown, Alec Radford, Dario Amodei, Paul Christiano, Geoffrey Irving
  - Keyword: Reward learning for language, Continuing text with positive sentiment, Summary task, Physical descriptive
  - Code: [official](https://github.com/openai/lm-human-preferences)
  - Dataset: [TL;DR](https://www.tensorflow.org/datasets/catalog/reddit), [CNN/DM](https://github.com/abisee/cnn-dailymail)
- [Scalable agent alignment via reward modeling: a research direction](https://arxiv.org/abs/1811.07871)
  - Jan Leike, David Krueger, Tom Everitt, Miljan Martic, Vishal Maini, Shane Legg
  - Keyword: Agent alignment problem, Learn reward from interaction, Optimize reward with RL, Recursive reward modeling
  - Code: [official](https://github.com/rddy/ReQueST)
  - Env: Atari
- [Reward learning from human preferences and demonstrations in Atari](https://arxiv.org/abs/1811.06521)
  - Borja Ibarz, Jan Leike, Tobias Pohlen, Geoffrey Irving, Shane Legg, Dario Amodei
  - Keyword: Expert demonstration trajectory preferences reward hacking problem, Noise in human label
  - Code: [official](https://github.com/rddy/ReQueST)
  - Env: Atari
- [Deep TAMER: Interactive Agent Shaping in High-Dimensional State Spaces](https://arxiv.org/abs/1709.10163)
  - Garrett Warnell, Nicholas Waytowich, Vernon Lawhern, Peter Stone
  - Keyword:  High dimension state, Leverage the input of Human trainer
  - Code: [third party](https://github.com/bharadwaj1098/Tamer)
  - Env: Atari
- [Deep reinforcement learning from human preferences](https://arxiv.org/abs/1706.03741)
  - Paul Christiano, Jan Leike, Tom B. Brown, Miljan Martic, Shane Legg, Dario Amodei
  - Keyword: Explore goal defined in human preferences between pairs of trajectories segmentation, Learn more complex thing than human feedback
  - Code: [official](https://github.com/mrahtz/learning-from-human-preferences)
  - Env: Atari, MuJoCo
- [Interactive Learning from Policy-Dependent Human Feedback](https://arxiv.org/abs/1701.06049)
  - James MacGlashan, Mark K Ho, Robert Loftin, Bei Peng, Guan Wang, David Roberts, Matthew E. Taylor, Michael L. Littman
  - Keyword: Decision is influenced by current policy rather than human feedback, Learn from policy dependent feedback that converges to a local optimal

## Codebases
```
format:
- [title](codebase link) [links]
  - author1, author2, and author3...
  - keyword
  - experiment environments, datasets or tasks
```

- [LLaMA2 + RLHF - DeepSpeed + Ray](https://github.com/OpenLLMAI/OpenLLaMA2)
  - OpenLLMAI
  - Keyword: LLaMA2, RLHF, DeepSpeed, Ray
  - Task: Open-source implementation of Industrial-grade High-performance LLaMA2 RLHF including PPO/RS, etc.
- [PaLM + RLHF - Pytorch](https://github.com/lucidrains/PaLM-rlhf-pytorch)
  - Phil Wang, Yachine Zahidi, Ikko Eltociear Ashimine, Eric Alcaide
  - Keyword: Transformers, PaLM architecture
  - Dataset: [enwik8](http://prize.hutter1.net/)
- [lm-human-preferences](https://github.com/openai/lm-human-preferences)
  - Daniel M. Ziegler, Nisan Stiennon, Jeffrey Wu, Tom B. Brown, Alec Radford, Dario Amodei, Paul Christiano, Geoffrey Irving
  - Keyword: Reward learning for language, Continuing text with positive sentiment, Summary task, Physical  descriptive
  - Dataset: [TL;DR](https://www.tensorflow.org/datasets/catalog/reddit), [CNN/DM](https://github.com/abisee/cnn-dailymail)
- [following-instructions-human-feedback](https://github.com/openai/following-instructions-human-feedback)
  - Long Ouyang, Jeff Wu, Xu Jiang, et al.
  - Keyword: Large Language Model, Align Language Model with Human Intent
  - Dataset: [TruthfulQA](https://github.com/sylinrl/TruthfulQA) [RealToxicityPrompts](https://allenai.org/data/real-toxicity-prompts)
- [Transformer Reinforcement Learning (TRL)](https://github.com/lvwerra/trl)
  - Leandro von Werra, Younes Belkada, Lewis Tunstall, et al.
  - Keyword: Train LLM with RL, PPO, Transformer
  - Task: [IMDB sentiment](https://www.imdb.com/interfaces/)
- [Transformer Reinforcement Learning X (TRLX)](https://github.com/CarperAI/trlx)
  - Jonathan Tow, Leandro von Werra, et al.
  - Keyword: Distributed training framework, T5-based language models, Train LLM with RL, PPO, ILQL
  - Task: Fine tuning LLM with RL using provided reward function or reward-labeled dataset
- [RL4LMs (A modular RL library to fine-tune language models to human preferences)](https://github.com/allenai/RL4LMs)
  - Rajkumar Ramamurthy, Prithviraj Ammanabrolu, Kianté,Brantley, Jack Hessel, Rafet Sifa, Christian Bauckhage, Hannaneh Hajishirzi, Yejin Choi
  - Keyword: Optimizing language generators with RL, Benchmark,  Performant RL algorithm
  - Dataset: [IMDB](https://www.imdb.com/interfaces/), [CommonGen](https://inklab.usc.edu/CommonGen/), [CNN Daily Mail](https://github.com/abisee/cnn-dailymail), [ToTTo](https://github.com/google-research-datasets/ToTTo), [WMT-16 (en-de)](https://www.statmt.org/wmt16/it-translation-task.html), [NarrativeQA](https://github.com/deepmind/narrativeqa), [DailyDialog](http://yanran.li/dailydialog)
- [LaMDA-rlhf-pytorch](https://github.com/conceptofmind/LaMDA-rlhf-pytorch)
  - Phil Wang
  - Keyword: LaMDA, Attention-mechanism
  - Task: Open-source pre-training implementation of Google's LaMDA research paper in PyTorch
- [TextRL](https://github.com/voidful/TextRL)
  - Eric Lam
  - Keyword: huggingface's transformer
  - Task: Text generation
  - Env: PFRL, gym
- [minRLHF](https://github.com/thomfoster/minRLHF)
  - Thomfoster
  - Keyword: PPO, Minimal library
  - Task: educational purposes
- [DeepSpeed-Chat](https://github.com/microsoft/DeepSpeedExamples/tree/master/applications/DeepSpeed-Chat)
  - Microsoft
  - Keyword: Affordable RLHF Training
- [Dromedary](https://github.com/IBM/Dromedary)
  - IBM
  - Keyword: Minimal human supervision, Self-aligned
  - Task: Self-aligned language model trained with minimal human supervision
- [FG-RLHF](https://finegrainedrlhf.github.io/)
  - Zeqiu Wu, Yushi Hu, Weijia Shi, et al.
  - Keyword: Fine-Grained RLHF, providing a reward after every segment, Incorporating multiple RMs associated with different feedback types
  - Task: A framework that enables training and learning from reward functions that are fine-grained in density and multiple RMs
-[Safe-RLHF](https://github.com/PKU-Alignment/safe-rlhf)
  - Xuehai Pan, Ruiyang Sun, Jiaming Ji, et al.
  - Keyword: Support popular pre-trained models, Large human-labeled dataset, Multi-scale metrics for safety constraints verification, Customized parameters
  - Task: Constrained Value-Aligned LLM via Safe RLHF

## Dataset
```
format:
- [title](dataset link) [links]
  - author1, author2, and author3...
  - keyword
  - experiment environments or tasks
```
- [HH-RLHF](https://github.com/anthropics/hh-rlhf)
  - Ben Mann, Deep Ganguli
  - Keyword: Human preference dataset, Red teaming data, machine-written
  - Task: Open-source dataset for human preference data about helpfulness and harmlessness
- [Stanford Human Preferences Dataset(SHP)](https://huggingface.co/datasets/stanfordnlp/SHP)
  - Ethayarajh, Kawin and Zhang, Heidi and Wang, Yizhong and Jurafsky, Dan
  - Keyword: Naturally occurring and human-written dataset,18 different subject areas
  - Task: Intended to be used for training RLHF reward models
- [PromptSource](https://github.com/bigscience-workshop/promptsource)
  - Stephen H. Bach, Victor Sanh, Zheng-Xin Yong et al.
  - Keyword: Prompted English datasets,  Mapping a data example into natural language
  - Task:  Toolkit for creating, Sharing and using natural language prompts
- [Structured Knowledge Grounding(SKG) Resources Collections](https://unifiedskg.com/)
  - Tianbao Xie, Chen Henry Wu, Peng Shi et al.
  - Keyword: Structured Knowledge Grounding
  - Task:  Collection of datasets are related to structured knowledge grounding
- [The Flan Collection](https://github.com/google-research/FLAN/tree/main/flan/v2)
  - Longpre Shayne, Hou Le, Vu Tu et al.
  - Task: Collection compiles datasets from Flan 2021, P3, Super-Natural Instructions 
- [rlhf-reward-datasets](https://huggingface.co/datasets/yitingxie/rlhf-reward-datasets)
  - Yiting Xie
  - Keyword: Machine-written dataset
- [webgpt_comparisons](https://huggingface.co/datasets/openai/webgpt_comparisons)
  - OpenAI
  - Keyword: Human-written dataset, Long form question answering 
  - Task:  Train a long form question answering model to align with human preferences
- [summarize_from_feedback](https://huggingface.co/datasets/openai/summarize_from_feedback)
  - OpenAI
  - Keyword: Human-written dataset, summarization
  - Task:  Train a summarization model to align with human preferences
- [Dahoas/synthetic-instruct-gptj-pairwise](https://huggingface.co/datasets/Dahoas/synthetic-instruct-gptj-pairwise)
  - Dahoas
  - Keyword: Human-written dataset, synthetic dataset
- [Stable Alignment - Alignment Learning in Social Games](https://github.com/agi-templar/Stable-Alignment)
  - Ruibo Liu, Ruixin (Ray) Yang, Qiang Peng
  - Keyword: Interaction data used for alignment training, Run in Sandbox
  - Task: Train on the recorded interaction data in simulated social games
- [LIMA](https://huggingface.co/datasets/GAIR/lima)
  - Meta AI
  - Keyword: without any RLHF, few carefully curated prompts and responses
  - Task: Dataset used for training the LIMA model



## Blogs

- [OpenAI] [ChatGPT: Optimizing Language Models for Dialogue](https://openai.com/blog/chatgpt)
- [Hugging Face] [Illustrating Reinforcement Learning from Human Feedback (RLHF)](https://huggingface.co/blog/rlhf)
- [ZhiHu] [通向AGI之路：大型语言模型 (LLM) 技术精要](https://zhuanlan.zhihu.com/p/597586623)
- [ZhiHu] [大语言模型的涌现能力：现象与解释](https://zhuanlan.zhihu.com/p/621438653)
- [ZhiHu] [中文hh-rlhf数据集上的ppo实践](https://zhuanlan.zhihu.com/p/652044120)
- [W&B Fully Connected][ Understanding Reinforcement Learning from Human Feedback (RLHF)](https://wandb.ai/ayush-thakur/RLHF/reports/Understanding-Reinforcement-Learning-from-Human-Feedback-RLHF-Part-1--VmlldzoyODk5MTIx)
- [Deepmind] [Learning through human feedback](https://www.deepmind.com/blog/learning-through-human-feedback)
- [Notion] [深入理解语言模型的突现能力](https://yaofu.notion.site/514f4e63918749398a1a8a4c660e0d5b)
- [Notion] [拆解追溯 GPT-3.5 各项能力的起源](https://yaofu.notion.site/GPT-3-5-360081d91ec245f29029d37b54573756#cf00f4e11d974187956122ce7d534386)
- [gist] [Reinforcement Learning for Language Models](https://gist.github.com/yoavg/6bff0fecd65950898eba1bb321cfbd81)
- [YouTube] [John Schulman - Reinforcement Learning from Human Feedback: Progress and Challenges](https://www.youtube.com/watch?v=hhiLw5Q_UFg)
- [OpenAI / Arize] [OpenAI on Reinforcement Learning With Human Feedback](https://arize.com/blog/openai-on-rlhf/)


## Other Language Support

[Turkish](README_TU.md)

## Contributing

Our purpose is to make this repo even better. If you are interested in contributing, please refer to [HERE](CONTRIBUTING.md) for instructions in contribution.

## License

Awesome RLHF is released under the Apache 2.0 license.
