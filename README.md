# GSGN
Code for paper [*Optimizing Speech Multi-View Feature Fusion through Conditional Computation*](https://arxiv.org/abs/2501.08057)

The paper has been accepted by ICASSP 2025.

**We'll be releasing the code and more detailed soon.**

[English](README.md) | [Chinese](README_ZH.md)

## Method

**Motivation** We observed that while S-features exhibit rapid convergence, they fail to outperform FBanks features.

![FBanks vs S-features](Figures/convergence.png)

**Architecture** we propose a novel generalized feature fusion framework grounded in conditional computation, featuring a gradient-sensitive gating network and a multi-stage dropout strategy

![Architecture](Figures/arch.png)

**Result**

![S-feature from HuBERT model](Figures/result_hubert.png)

![S-feature from WavLM model](Figures/result_wavlm.png)

## Train

## Inference

## Citation

```bibtex
@misc{shan2025optimizingspeechmultiviewfeature,
      title={Optimizing Speech Multi-View Feature Fusion through Conditional Computation}, 
      author={Weiqiao Shan and Yuhao Zhang and Yuchen Han and Bei Li and Xiaofeng Zhao and Yuang Li and Min Zhang and Hao Yang and Tong Xiao and Jingbo Zhu},
      year={2025},
      eprint={2501.08057},
      archivePrefix={arXiv},
      primaryClass={eess.AS},
      url={https://arxiv.org/abs/2501.08057}, 
}