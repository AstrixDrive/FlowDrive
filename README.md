<div align="center">
<h3>IRL-VLA: Training an Vision-Language-Action Policy via Reward World Model</h3>

<a href="https://arxiv.org/abs/{}"><img src='https://img.shields.io/badge/Paper-FlowDrive-blue?logo=arxiv' alt='Paper PDF'></a>
<a href="https://github.com/IRL-VLA/{}"><img src='https://img.shields.io/badge/%E2%9C%A8Weights-FlowDrive-red' alt='HuggingFace'></a>
<a href="https://astrixdrive.github.io/FlowDrive.github.io/"><img src='https://img.shields.io/badge/ProjectPage-FlowDrive-green?logo=githubpages' alt='HuggingFace'></a>
<!-- <a href="https://ieeexplore.ieee.org/document/10592819"><img src='https://img.shields.io/badge/arXiv-SemanticFormer-blue' alt='Paper PDF'></a>
<a href="https://www.arxiv.org/pdf/2508.01778"><img src='https://img.shields.io/badge/Datasets-MaplessQCNet-red' alt='Datasets'></a>
<a href="https://www.arxiv.org/pdf/2508.01778"><img src='https://img.shields.io/badge/Datasets-Sparse4D-green' alt='Datasets'></a> -->

![visualization_example](assets/example2.gif)
</div>


## Overview

![github_irlVLA](assets/framework.png)

## Abstract         

Recent advances in end-to-end autonomous driving leverage multi-view images to construct bird’s-eye-view (BEV) representations for environment understanding and motion prediction. While BEV features offer a compact and holistic encoding of the driving scene, they inherently lack explicit modeling of risk and guidance priors for safe and interpretable planning. In addition, existing frameworks often tightly couple motion pattern prediction with trajectory generation within the planning module, limiting flexibility and undermining the system's ability to generalize across diverse driving scenarios. To address these challenges, we propose FlowDrive, a novel motion-decoupled end-to-end driving framework based on flow field modeling. FlowDrive introduces risk potential fields and lane attraction fields, to construct continuous and physically interpretable motion flow fields that represent both dynamic and static elements in the environment. These flow-based representations augment BEV features with fine-grained safety-aware guidance, enabling more robust and rational trajectory planning. Furthermore, we incorporate an adaptive anchor refinement mechanism, which dynamically dynamically adjusts trajectory anchors to evolving scene context, improving planning precision and responsiveness. Furthermore, FlowDrive decouples motion-mode prediction from trajectory generation, enhancing planning interpretability and flexibility. Extensive experiments conducted on the NAVSIM v2 autonomous driving benchmark demonstrate that FlowDrive achieves state-of-the-art performance, reaching an EPDMS score of 86.3, significantly outperforming other baselines.



## News
`[2025/09/12]` [ArXiv](https://arxiv.org/abs/{}) paper release. Code/Models are coming soon. Please stay tuned! ☕️\

## Updates
We are going to release code step by step:

- [ ] Code for flow field construction
- [ ] Weights of model
- [ ] tutorial for installation
- [ ] initial repo & main paper

Note: Code needs to be cleaned and I will open source all the code within next several month. As I promised.

## 📄 Citation

If you find FlowDrive is useful in your research or applications, please consider giving us a star 🌟 and citing it by the following BibTeX entry.

```bibtex
xxx
```

