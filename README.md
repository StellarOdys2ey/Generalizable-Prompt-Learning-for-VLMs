# Generalizable-Prompt-Learning-for-VLMs
A curated list of prompt learning methods for vision-language models which can be used for base-to-novel generalizaiton.

### Tips:
- All the papers included in this list contain **base-to-novel generalization experiments**. In other words, methods that do not demonstrate generalization capabilities are not listed here.
- The layout of this list is inspired by [this](https://github.com/zhengli97/Awesome-Prompt-Adapter-Learning-for-VLMs) repository, which is initiated and maintained by **[Zheng Li](https://zhengli97.github.io/)**. He is currently a third-year Ph.D. student at Nankai University, with one more CCF A-level paper to be published before graduation. I wish him success in his further research and happy trail running.
- I was saddened to unexpectedly find that **[Yaohui Li (1997-2024)](https://leonardo-lyh.github.io/)**, the second author of **Conditional Prototype Rectification Prompt Learning (CPR, TCSVT 2025)**, tragically passed away in an accident after completing this work. In his homepage, his education timeline noted his PhD as expected to span from 2023 to 2027, but sadly, his 2027 will never come. Although I did not know him personally, I extend my heartfelt gratitude for his contributions to the field of prompt learning, and I hope that his legacy will inspire others to build upon his vision. May you rest in peace.

# <div style="font-size: 10px;">Table of Contents</div>

- [Papers](#papers)
    - [Published in 2025](#Published-in-2025)

## Keywords
![](https://img.shields.io/badge/Text-green) Use text-based parameter-efficient fine-tuning.

![](https://img.shields.io/badge/Image-orange) Use image-based parameter-efficient fine-tuning.

![](https://img.shields.io/badge/Image--Text-blue) Use text- and image-based parameter-efficient fine-tuning.

## Published in 2025
- `TextRefiner` **TextRefiner: Internal Visual Feature as Efficient Refiner for Vision-Language Models Prompt Tuning**    AAAI 2025.     
[[Paper LinK](https://arxiv.org/abs/2412.08176)] [[Code Link](https://github.com/xjjxmu/TextRefiner)]![](https://img.shields.io/badge/Text-green)
- `ProText` **Learning to Prompt with Text Only Supervision for Vision-Language Models**    AAAI 2025.  
[[Paper Link](https://arxiv.org/abs/2401.02418)] [[Code Link](https://github.com/muzairkhattak/ProText)] ![](https://img.shields.io/badge/Text-green)
- `SPTR` **A Similarity Paradigm Through Textual Regularization Without Forgetting**    AAAI 2025.  
[[Paper Link](https://arxiv.org/abs/2502.14376)] [No code available] ![](https://img.shields.io/badge/Image--Text-blue)
- `FATE` **FATE: Feature-Adapted Parameter Tuning for Vision-Language Models**    AAAI 2025.  
[[Paper Link](https://ojs.aaai.org/index.php/AAAI/article/view/32975)] [No code available] ![](https://img.shields.io/badge/Text-green)
- `PTinCAS` **Prompt Tuning In a Compact Attribute Space**    AAAI 2025.  
[[Paper Link](https://ojs.aaai.org/index.php/AAAI/article/view/32365)] [No code available] ![](https://img.shields.io/badge/Text-green)
- `DsRA` **Exploring the Better Multimodal Synergy Strategy for Vision-Language Models**    AAAI 2025.  
[[Paper Link](https://ojs.aaai.org/index.php/AAAI/article/view/34372)] [No code available] ![](https://img.shields.io/badge/Image--Text-blue)
- `CLIP-AST` **Adaptive Parameter Selection for Tuning Vision-Language Models**    CVPR 2025.  
[[Paper Link](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhang_Adaptive_Parameter_Selection_for_Tuning_Vision-Language_Models_CVPR_2025_paper.pdf)] [No code available] ![](https://img.shields.io/badge/Image--Text-blue)
- `MMRL` **MMRL: Multi-Modal Representation Learning for Vision-Language Models**    CVPR 2025.  
[[Paper Link](https://arxiv.org/abs/2503.08497)] [[Code Link](https://github.com/yunncheng/MMRL)] ![](https://img.shields.io/badge/Image--Text-blue)
- `DPC` **DPC: Dual-Prompt Collaboration for Tuning Vision-Language Models**    CVPR 2025.   
[[Paper Link](https://arxiv.org/abs/2503.13443)] [[Code Link](https://github.com/JREion/DPC)] ![](https://img.shields.io/badge/Text-green)   
- `2SFS` **Rethinking Few-Shot Adaptation of Vision-Language Models in Two Stages**   CVPR 2025.  
[[Paper Link](https://arxiv.org/abs/2503.11609)] [[Code Link](https://github.com/FarinaMatteo/rethinking_fewshot_vlms)]![](https://img.shields.io/badge/Image--Text-blue)   
- `SkipT` **Skip Tuning: Pre-trained Vision-Language Models are Effective and Efficient Adapters Themselves**    CVPR 2025.    
[[Paper Link](https://arxiv.org/abs/2412.11509)] [[Code Link](https://github.com/Koorye/SkipTuning)]  ![](https://img.shields.io/badge/Image--Text-blue)
- `TAC` **Task-Aware Clustering for Prompting Vision-Language Models**    CVPR 2025.   
[[Paper Link](https://openaccess.thecvf.com/content/CVPR2025/papers/Hao_Task-Aware_Clustering_for_Prompting_Vision-Language_Models_CVPR_2025_paper.pdf)] [[Code Link](https://github.com/FushengHao/TAC)] ![](https://img.shields.io/badge/Image--Text-blue)     
- `ATPrompt` **Advancing Textual Prompt Learning with Anchored Attributes**    ICCV 2025.   
[[Paper Link](https://arxiv.org/abs/2412.09442)] [[Code Link](https://github.com/zhengli97/ATPrompt)]![](https://img.shields.io/badge/Text-green)
- `CaPL` **Causality-guided Prompt Learning for Vision-language Models via Visual Granulation**    ICCV 2025.   
[No paper available] [[Code Link](https://github.com/GaoMY-521/CaPL_Code)]![](https://img.shields.io/badge/Image--Text-blue)
- `HicroPL` **Hierarchical Cross-modal Prompt Learning for Vision-Language Models**    ICCV 2025.   
[[Paper Link](https://arxiv.org/abs/2507.14976)] [[Code Link(empty)](https://github.com/zzeoZheng/HiCroPL)]![](https://img.shields.io/badge/Image--Text-blue)
- `FM` **Enhancing Target-unspecific Tasks through a Features Matrix**    ICML 2025.   
[[Paper Link](https://arxiv.org/abs/2505.03414)] [No code available]![](https://img.shields.io/badge/Text-Green)
- `SurPL` **Surrogate Prompt Learning: Towards Efficient and Diverse Prompt Learning for Vision-Language Models**    ICML 2025.   
[[Paper Link](https://openreview.net/pdf?id=zjG9GRG462)] [[Code Link](https://github.com/llcllc1997/SurPL)]![](https://img.shields.io/badge/Image--Text-blue)
- `TAP` **Tree of Attributes Prompt Learning For Vision Language Models**    ICLR 2025.   
[[Paper Link](https://arxiv.org/abs/2410.11201)] [[Code Link](https://github.com/HHenryD/TAP)]![](https://img.shields.io/badge/Image--Text-blue)
- `DeKg` **Divergence-enhanced Knowledge-guided Context Optimization for Visual-Language Prompt Tuning**    ICLR 2025.   
[[Paper Link](https://openreview.net/pdf?id=6wOmHdwCC4)] [[Code Link](https://github.com/cnunlp/DeKg)]![](https://img.shields.io/badge/Text-Green)
- `DiSa` **DiSa: Directional Saliency-Aware Prompt Learning for Generalizable Vision-Language Models**    KDD 2025.   
[[Paper Link](https://arxiv.org/abs/2505.19373)] [No code available]![](https://img.shields.io/badge/Image--Text-blue)
- `BIP` **Bi-modality Individual-aware Prompt tuning for Visual-Language Model**    TPAMI 2025.   
[[Paper Link](https://ieeexplore.ieee.org/abstract/document/10949734)] [[Code Link](https://github.com/htyao89/BIP)]![](https://img.shields.io/badge/Image--Text-blue)  
- `CPR` **Conditional Prototype Rectification Prompt Learning**    TCSVT 2025.   
[[Paper Link](https://ieeexplore.ieee.org/abstract/document/11069290)] [[Code Link](https://github.com/chenhaoxing/CPR)]![](https://img.shields.io/badge/Image--Text-blue)
- `LwEIB` **Learning with Enriched Inductive Biases for Vision-Language Models**    IJCV 2025.   
[[Paper Link](https://link.springer.com/article/10.1007/s11263-025-02354-1)] [[Code Link](https://github.com/ZjjConan/VLM-LwEIB)]![](https://img.shields.io/badge/Image--Text-blue)  
