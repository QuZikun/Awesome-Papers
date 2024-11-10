# Awesome Papers

## ✨ About
This repo contains a curated list of **MLLM/LLM/DL/Diffusion** papers relating to AI domain.
Please feel free to send pull requests or [email](qzk0919@connect.hku.hk) me to add papers! 
This version of the repository may have some typos, so don’t hesitate to contact me for corrections!

<!-- ******* 0-Content Table ******* -->
 ## 🏠 Table of Contents
- [Catastrophic Forgetting](#catastrophic-forgetting)
  - [Abstract](#abstract)
  - [Problem Setting](#problem-setting)
  - [Awesome Papers](#awesome-papers)
    
-[Diffusion Model](#Diffusion-Model)
  -[Abstract](#abstract)
  - [Awesome Papers](#awesome-papers)



<!-- ******* 1-Catastrophic Forgetting******* -->
## 📄 Catastrophic Forgetting
## 🐳Abstract
> Forgetting refers to the loss or deterioration of previously acquired information or knowledge. While the existing surveys on forgetting have primarily focused on continual learning, forgetting is a prevalent phenomenon observed in various other research domains within deep learning. Forgetting manifests in research fields such as generative models due to generator shifts, and federated learning due to heterogeneous data distributions across clients. Addressing forgetting encompasses several challenges, including balancing the retention of old task knowledge with fast learning of new tasks, managing task interference with conflicting goals, and preventing privacy leakage, etc. Moreover, most existing surveys on continual learning implicitly assume that forgetting is always harmful. In contrast, our survey argues that forgetting is a double-edged sword and can be beneficial and desirable in certain cases, such as privacy-preserving scenarios. By exploring forgetting in a broader context, we aim to present a more nuanced understanding of this phenomenon and highlight its potential advantages. Through this comprehensive survey, we aspire to uncover potential solutions by drawing upon ideas and approaches from various fields that have dealt with forgetting. By examining forgetting beyond its conventional boundaries, in future work, we hope to encourage the development of novel strategies for mitigating, harnessing, or even embracing forgetting in real applications.

## 🙋Problem Setting
| **Problem Setting** | **Goal** | **Source of forgetting** | 
| --------------- | :---- | :---- | :---- |
| Continual Learning | learn non-stationary data distribution without forgetting previous knowledge  | data-distribution shift during training |
| Foundation Model |unsupervised learning on large-scale unlabeled data | data-distribution shift in pre-training, fine-tuning  |
| Domain Adaptation | adapt to target domain while maintaining performance on source domain | target domain sequentially shift over time |
| Test-time Adaptation |mitigate the distribution gap between training and testing | adaptation to the test data distribution during testing|
| Meta-Learning | learn adaptable knowledge to new tasks | incrementally meta-learn new classes / task-distribution shift  |
| Generative Model | learn a generator to appriximate real data distribution | generator shift/data-distribution shift |
| Reinforcement Learning | maximize accumulate rewards | state, action, reward and state transition dynamics|
| Federated Learning | decentralized training without sharing data |  model average; non-i.i.d data; data-distribution shift |

<!-- | Self-Supervised Learning | unsupervised pre-training | data-distribution shift | -->

## 📝 Awesome Papers
|  Title  |   Venue  |   Date   |   Code   |   Notes  |   Harm or Benefit  |
|:--------|:--------:|:--------:|:--------:|:--------:| :--------:|
| [**MoFO: Momentum-Filtered Optimizer for Mitigating Forgetting in LLM Fine-Tuning**](https://arxiv.org/pdf/2407.20999v2) | arXiv | 2024-07-31 | ! null | Forgetting in Fine-Tuning Foundation LLM | harm |
| [**Model Tailor: Mitigating Catastrophic Forgetting in Multi-modal Large Language Models**](https://arxiv.org/abs/2402.12048) | arXiv | 2024-02-19 | ! null | Ensemble to mitigate forgetting in MLLM| harm |
| [**Continual Learning for Large Language Models: A Survey**](https://arxiv.org/pdf/2402.01364) | arXiv | 2024-02-07 | ! null | Continual Learning in LLM | survey |
| [**A Comprehensive Survey of Continual Learning: Theory, Method and Application**](https://arxiv.org/abs/2302.00487) | arXiv | 2023-01-31 | ! null | Continual Learning in LLM | survey |
| [**Divide and not forget: Ensemble of selectively trained experts in Continual Learning**](https://arxiv.org/abs/2401.10191) | arXiv | 2024-01-18 | https://github.com/grypesc/SEED | Architecture based method to mitigate CF | harm |

<!-- ******* 2-Diffusion Model******* -->
## 📄 Diffusion Model
## 🐳Abstract
>
## 📝 Awesome Papers
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Brain Diffusion for Visual Exploration: Cortical Discovery using Large Scale Generative Models**](https://arxiv.org/abs/2306.03089) | arXiv | 2023-06-05 | https://github.com/aluo-x/BrainDiVE | Brain diffusion |
