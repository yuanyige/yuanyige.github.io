---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---


<span class='anchor' id='about-me'></span>


<!-- # Introduction -->

<span class='anchor' id='about-me'></span>

I am currently pursuing my Ph.D. at the State Key Laboratory of AI Safety, advised by Prof. Xueqi Cheng and Assoc. Prof. Bingbing Xu.

My research goal is to build Trustworthy AI that performs reliably and ethically for social good and human well-being.
To achieve this, I worked on generalization, alignment and agentic system across the domains of graph, vision, and language. My research includes:

- **Machine Learning Generalization**: To make models generalize stably under domain shifts, noises, or perturbations. 

- **Large Language Model Alignment**: To align large language models with human values and safety requirements.

- **Agent System Reasoning and Planning**: To enhance agent's logical reasoning and strategic planning for complex tasks.


# 🔥 News 

<span class='anchor' id='-news'></span>
- _2025.07_: &nbsp;🥳 We're excited to host "The 1st Workshop on LLM Agents for Social Simulation" at CIKM 2025 in Seoul, Korea!
- _2025.06_: &nbsp;🎖 I received the President Award of the Chinese Academy of Sciences (CAS), the **highest honor** for CAS students.
- _2025.05_: &nbsp;🎉🎉 One paper is accepted in ACL 2025.
- _2025.04_: &nbsp;🎉🎉 Two papers are accepted in SIGIR 2025.
- _2025.03_: &nbsp;🥳 Our paper, [SimPER](https://arxiv.org/abs/2502.00883), has been adopted by [LG AI Research](https://www.lgresearch.ai) as the core training algorithm for their [EXAONE Deep](https://arxiv.org/abs/2503.12524) series LLMs, helping their 32B model surpass the performance of DeepSeek R1 (671B)!
- _2025.02_: &nbsp;🥇 Our team won first place in the [AgentSociety Challenge @ WWW 2025](https://tsinghua-fib-lab.github.io/AgentSocietyChallenge).
- _2025.01_: &nbsp;🎉🎉 Our paper [SimPER: A Minimalist Approach to Preference Alignment without Hyperparameters](https://openreview.net/forum?id=jfwe9qNqRi) is accepted in ICLR 2025.
- _2025.01_: &nbsp;🎉🎉 Our paper [On a Connection Between Imitation Learning and RLHF](https://openreview.net/forum?id=2QdsjiNXgj) is accepted in ICLR 2025.
- _2024.11_: &nbsp;🎖 I received the National Scholarship in 2024.
- _2024.09_: &nbsp;🎉🎉 Our paper [Cal-DPO: Calibrated Direct Preference Optimization for Language Model Alignment](https://openreview.net/forum?id=57OQXxbTbY&noteId=ellZ40SC5c) is accepted in NeurIPS 2024.
- _2024.09_: &nbsp;🎉🎉 Our paper [How to Leverage Demonstration Data in Alignment for Large Language Model? A Self-Imitation Learning Perspective](https://openreview.net/forum?id=QHmEtCEGFO) is accepted in EMNLP 2024.

# 📝 Selected Publications  <a href="/publications.html" style="font-size:16px"> [FullList]


<span class='anchor' id='-publications'></span>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='/resources/w2sr-pic.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Incentivizing Strong Reasoning from Weak Supervision](https://arxiv.org/abs/2505.20072)

**Yige Yuan\***, Teng Xiao*, Shuchang Tao, Xue Wang, Jinyang Gao, Bolin Ding, Bingbing Xu

- We study the problem of incentivizing reasoning of LLMs from weak supervision, and find that weak reasoner teachers—4.7× smaller and 31.5% less performant than the student—can boost student reasoning by 56.25% without expert supervision or costly RL.

([**Paper**](https://arxiv.org/pdf/2505.20072))([**Code**](https://github.com/yuanyige/w2sr))([**Slides**](#))([**Poster**](#))
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025 Bi-Align</div><img src='/resources/sea-pic.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Inference-time Alignment in Continuous Space](https://openreview.net/pdf?id=9teQltJgBo)

**Yige Yuan\***, Teng Xiao*, Yunfan Li, Bingbing Xu, Shuchang Tao, Yunqi Qiu, Huawei Shen, Xueqi Cheng

- We propose SEA, a simple inference-time alignment method that reformulates alignment as an iterative optimization procedure on an energy function over logits in the continuous space defined by the optimal RLHF policy for deep and effective alignment.

([**Paper**](https://openreview.net/pdf?id=9teQltJgBo))([**Code**](https://github.com/yuanyige/sea))([**Slides**](#))([**Poster**](#))
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='/resources/iclr2025-simper-pic.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SimPER: A Minimalist Approach to Preference Alignment without Hyperparameters](https://arxiv.org/abs/2502.00883)

Teng Xiao*, **Yige Yuan\***, Zhengyu Chen, Mingxiao Li, Shangsong Liang, Zhaochun Ren, Vasant G Honavar

- We propose SimPER, a simple yet effective hyperparameter-free alignment method that optimizes inverse perplexity. This lightweight objective eliminates the need for costly hyperparameter tuning and reference models, while theoretically optimizing total variation distance (TVD) and mitigating likelihood displacement issues.

([**Paper**](https://arxiv.org/pdf/2502.00883))([**Code**](https://github.com/tengxiao1/SimPER))([**Slides**](#))([**Poster**](/resources/iclr2025-simper-poster.pdf))
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='/resources/iclr2025-dil-pic.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[On a Connection Between Imitation Learning and RLHF](https://openreview.net/forum?id=2QdsjiNXgj)

Teng Xiao, **Yige Yuan**, Mingxiao Li, Zhengyu Chen, Vasant G Honavar

- This work reveals that RLHF is barely RL and secretly performs imitation learning (IL) and propose DIL, a principled framework that directly optimizes IL. DIL unifies existing alignment methods as special cases while enabling new variants, offering fresh insights into alignment through the lens of imitation learning.

([**Paper**](https://openreview.net/forum?id=2QdsjiNXgj))([**Code**](https://github.com/tengxiao1/DIL))([**Slides**](#))([**Poster**](/resources/iclr2025-dil-poster.pdf))
</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='/resources/cvpr2024-tea-pic.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TEA: Test-time Energy Adaptation](https://arxiv.org/abs/2311.14402)

**Yige Yuan**, Bingbing Xu, Liang Hou, Fei Sun, Huawei Shen, Xueqi Cheng

- We propose to investigate generalization from an energy-based perspective and introduce TEA, a test-time adaptation method which transforms the trained classifier into an energy-based model and aligns the model's distribution with the test data's, enhancing its ability to perceive test distributions and thus improving overall generalizability.

([**Paper**](https://arxiv.org/pdf/2311.14402))([**Code**](https://github.com/yuanyige/tea))([**Slides**](/resources/cvpr2024-tea-slides.pdf))([**Poster**](/resources/cvpr2024-tea-poster.pdf))
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2024</div><img src='/resources/aaai2024-pdeadd-pic.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ PDE+: Enhancing Generalization via PDE with Adaptive Distributional Diffusion](https://arxiv.org/abs/2305.15835)

**Yige Yuan**, Bingbing Xu, Bo Lin, Liang Hou, Fei Sun, Huawei Shen, Xueqi Cheng

- We propose to investigate generalization from PDE perspective and propose PDE-ADD framework. We introduce adaptive distributional diffusion into transport equation to enhance smoothness of its solution, thereby improving generalization directly via the underlying function of NN.

([**Paper**](https://arxiv.org/pdf/2305.15835))([**Code**](https://github.com/yuanyige/pde-add))([**Slides**](/resources/aaai2024-pdeadd-slides.pdf))([**Poster**](/resources/aaai2024-pdeadd-poster.pdf))
</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neural Networks</div><img src='/resources/nn-infoadv-pic.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Towards Generalizable Graph Contrastive Learning: An Information Theory Perspective](https://arxiv.org/abs/2211.10929)

**Yige Yuan**, Bingbing Xu, Huawei Shen, Qi Cao, Keting Cen, Wen Zheng, Xueqi Cheng

- We propose a GCL generalization ability metric and prove a MI upper bound for it from an information-theoretic perspective. Guided by the bound, we design an InfoAdv framework, which can be applied to current GCL models and achieves SOTA performance.

([**Paper**](https://arxiv.org/pdf/2211.10929))([**Code**](https://github.com/yuanyige/infoadv))([**Slides**](#))([**Poster**](#))
</div>
</div>



# 🎖 Awards && Honors
<span class='anchor' id='-honors-and-awards'></span>
- _2025_ President Award, Chinese Academy of Sciences
- _2025_ First place, AgentSociety Challenge @ WWW 2025
- _2024_ National Scholarship (PhD Students)
- _2024_ First-Class Scholarship, University of Chinese Academy of Sciences
- _2023_ President Award, Institute of Computing Technology
- _2022_ First-Class Scholarship, University of Chinese Academy of Sciences
- _2022_ Outstanding Student Award, University of Chinese Academy of Sciences
- _2019_ First Prize, 12th National College Students Information Security Contest
- _2017_ First Prize, 15th National Science and Technology Academic Competition of Challenge Cup


# 🧳 Experiences

- _2025.01 - Present_, **Tongyi Lab, Alibaba Group**.
  - Research Internship in Large Language Models and Multi-Agent Systems
  - Advisor: Senior Algorithm Engineer Shuchang Tao and Yunpeng Zhai

- _2020.09 - Present_, **Institute of Computing Technology, Chinese Academy of Seiences**.
  - Ph.D. in Computer Software and Theory
  - Advisor: Professor [Xueqi Cheng](https://scholar.google.com/citations?user=hY8aLqAAAAAJ) and Associate Professor [Bingbing Xu](https://scholar.google.com/citations?user=PSx2drgAAAAJ)

- _2016.09 - 2020.06_, **Xidian University**.
  - Department of Network and Information Security
  - B.S. in Information Security (Experimental Class)


# 💻 Invited Talks

<span class='anchor' id='-invited-talks'></span>
- NICE Webinar, On a Connection Between Imitation Learning and RLHF, March 2025 [\[video\]](https://www.bilibili.com/video/BV1LwXsYPEsV)
- AITime Youth PhD Talk, On a Connection Between Imitation Learning and RLHF, March 2025 [\[video\]](https://www.bilibili.com/video/BV11N91Y1EQw)
- LOGS Webinar, Partial Differential Equation-Driven Generalizable Neural Networks, March 2024 [\[video\]](https://www.bilibili.com/video/BV1QK421v7e6)
- AITime Webinar, TEA: Test-time Energy Adaptation, April 2024
- WizSci Webinar, PDE+: Enhancing Generalization via PDE with Adaptive Distributional Diffusion, Jan 2024


# 🎓 Academic Services

<span class='anchor' id='-academic-services'></span>

* **Conference Reviewers**: NeurIPS (2024, 2025), ICML 2025, ICLR 2025, AISTATS 2025, KDD 2025, WWW 2025, ACMMM 2025, AAAI 2025, IJCAI 2025, ACL 2025, EMNLP 2024, COLING 2025, ACL Rolling Review, MIDL 2025, IJCNN 2025

* **Journal Reviewers**: IEEE Transactions on Knowledge and Data Engineering (TKDE), Applied Intelligence (APIN), CAAI Transactions on Intelligence Technology





