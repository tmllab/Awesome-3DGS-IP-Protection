# Awesome 3D/4DGS IP Protection
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![arXiv](https://img.shields.io/badge/arXiv-2602.03878-B31B1B.svg)](https://arxiv.org/abs/2602.03878) [![Survey](https://img.shields.io/badge/Type-Survey-6FAFB0.svg)](#survey) [![3DGS](https://img.shields.io/badge/Topic-3D%20Gaussian%20Splatting-C9B458.svg)](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) [![IP Protection](https://img.shields.io/badge/Focus-IP%20Protection-E0A84F.svg)](#) [![Last Update](https://img.shields.io/badge/Updated-Actively-EADCC8.svg)](#)



A curated list of papers and resources on **Intellectual Property (IP) protection for 3D Gaussian Splatting (3DGS)**, including watermarking, steganography, tampering localization, and editing safeguards.

This repository is maintained alongside our survey and will be continuously updated.

<!-- <p align="center">
  <img src="framework.png" width="100%">
</p> -->

**Table of Contents**
- [Awesome 3DGS IP Protection](#awesome-3dgs-ip-protection)
  - [Survey](#survey)
  - [Data-level Protection](#data-level-protection)
    - [Watermarking](#watermarking)
    - [Steganography](#steganography)
    - [Tampering Localization](#tampering-localization)
    - [Traceability and Provenance](#traceability-and-provenance)
    - [Editing Safeguard](#editing-safeguard)
  - [Model-level Protection](#model-level-protection)
  - [Citation](#citation)



## Survey

- **[arXiv 2026]** Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey [[Paper](https://arxiv.org/abs/2602.03878)]


## Data-level Protection
### Watermarking
- **[arXiv 2026]** BitC-3DGS: High-Capacity 3D Gaussian Splatting Watermarking via Bit Compression [[Paper](https://arxiv.org/abs/2605.29583)]
- **[arXiv 2026]** 4D-GSW: Kinematic-Aware Spatio-Temporal Consistent Watermarking for 4D Gaussian Splatting [[Paper](https://arxiv.org/abs/2605.22342)]
- **[arXiv 2026]** GuardMarkGS: Unified Ownership Tracing and Edit Deterrence for 3D Gaussian Splatting [[Paper](https://arxiv.org/abs/2605.12919)]
- **[arXiv 2026]** Position: 3D Gaussian Splatting Watermarking Should Be Scenario-Driven and Threat-Model Explicit [[Paper](https://arxiv.org/abs/2602.02602)]
- **[CVPR 2026]** Robust3DGSW: Toward Robust Watermarking for Quantization-Aware 3D Gaussian Splatting [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_Robust3DGSW_Toward_Robust_Watermarking_for_Quantization-Aware_3D_Gaussian_Splatting_CVPR_2026_paper.html)]
- **[CVPR 2026]** Where, What, Why: Toward Explainable 3D-GS Watermarking [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Cai_Where_What_Why_Toward_Explainable_3D-GS_Watermarking_CVPR_2026_paper.html)]
- **[CVPR 2026]** Write Where It Matters: Policy-Guided Watermarks for 3D Gaussian Splatting [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Li_Write_Where_It_Matters_Policy-Guided_Watermarks_for_3D_Gaussian_Splatting_CVPR_2026_paper.html)]
- **[CVPR 2026]** Mark4D: Temporally-Consistent Watermarking for 4D Gaussian Splatting [[Paper](https://openaccess.thecvf.com/content/CVPR2026/html/Lee_Mark4D_Temporally-Consistent_Watermarking_for_4D_Gaussian_Splatting_CVPR_2026_paper.html)]
- **[ICASSP 2026]** S3-3DGS: Steering Spherical-Harmonic Subspaces for Secure 3DGS Watermarking [[Paper](https://ieeexplore.ieee.org/abstract/document/11460630)]
- **[AAAI 2026]** Fading the Digital Ink: A Universal Black-Box Attack Framework for 3DGS Watermarking Systems [[Paper](https://arxiv.org/abs/2508.07263)]
- **[AAAI 2026]** Can Protective Watermarking Safeguard the Copyright of 3D Gaussian Splatting? [[Paper](https://arxiv.org/abs/2511.22262)]
- **[ICLR 2026]** NGS-Marker: Robust Native Watermarking for 3D Gaussian Splatting [[Paper](https://openreview.net/forum?id=yli4zJhJB0)]
- **[ICLR 2026]** CompMarkGS: Robust Watermarking for Compressed 3D Gaussian Splatting [[Paper](https://openreview.net/forum?id=NXQvejGBFx)][[Code](https://github.com/kuai-lab/iclr26_CompMarkGS)]
- **[Pattern Recognition Letters 2026]** VoMarkSplat: Robust Watermarking for 3D Gaussian Splatting with Patch and Multi-Convolutional Voting [[Paper](https://www.sciencedirect.com/science/article/pii/S0167865526000711)]
- **[arXiv 2025]** X-SG^2S: Safe and Generalizable Gaussian Splatting with X-dimensional Watermarks [[Paper](https://arxiv.org/abs/2502.10475)]
- **[arXiv 2025]** GaussianSeal: Rooting Adaptive Watermarks for 3D Gaussian Generation Model [[Paper](https://arxiv.org/abs/2503.00531)]
- **[arXiv 2025]** GS-Marker: Generalizable and Robust Watermarking for 3D Gaussian Splatting [[Paper](https://arxiv.org/abs/2503.18718)]
- **[arXiv 2025]** RDSplat: Robust Watermarking for 3D Gaussian Splatting Against 2D and 3D Diffusion Editing [[Paper](https://arxiv.org/abs/2512.06774)]
- **[OpenReview 2025]** Mark3DGS: Protecting the Intellectual Property of 3D Gaussian Splatting with Robust Watermarking [[Paper](https://openreview.net/forum?id=cfxnpmYC7N)]
- **[CVPR 2025]** 3D-GSW: 3D Gaussian Splatting for Robust Watermarking [[Paper](https://openaccess.thecvf.com/content/CVPR2025/html/Jang_3D-GSW_3D_Gaussian_Splatting_for_Robust_Watermarking_CVPR_2025_paper.html)][[Code](https://github.com/kuai-lab/cvpr25_3D-GSW)]
- **[CVPR 2025]** GuardSplat: Efficient and Robust Watermarking for 3D Gaussian Splatting [[Paper](https://arxiv.org/abs/2411.19895)][[Code](https://github.com/NarcissusEx/GuardSplat)]
- **[ACMMM 2025]** MarkSplatter: Generalizable Watermarking for 3D Gaussian Splatting Model via Splatter Image Structure [[Paper](https://dl.acm.org/doi/10.1145/3746027.3758144)][[Code](https://github.com/kevinhuangxf/marksplatter)]
- **[TIFS 2025]** MantleMark: Migrating Watermarks from Multi-View Images to Radiance Fields via Frequency Modulation [[Paper](https://ieeexplore.ieee.org/document/11263898/)]
- **[ICPADS 2025]** 3D-MGW: A Memory-Efficient Grouped Watermark for Multi-Object 3D Gaussian Splatting [[Paper](https://ieeexplore.ieee.org/document/11322973)]
- **[PRCV 2025]** SplatID: Real-Time Lossless 3D Gaussian Splatting with Feature ID Generation and Frame Filtering [[Paper](https://link.springer.com/chapter/10.1007/978-981-95-5737-0_22)]
- **[arXiv 2024]** WATER-GS: Toward Copyright Protection for 3D Gaussian Splatting via Universal Watermarking [[Paper](https://arxiv.org/abs/2412.05695)]
- **[NeurIPS 2024]** GaussianMarker: Uncertainty-Aware Copyright Protection of 3D Gaussian Splatting [[Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/39cee562b91611c16ac0b100f0bc1ea1-Abstract-Conference.html)][[Code](https://github.com/kevinhuangxf/GaussianMarker)]


### Steganography
- **[arXiv 2026]** Splats in Splats++: Robust and Generalizable 3D Gaussian Splatting Steganography [[Paper](https://arxiv.org/abs/2604.15862)]
- **[ICML 2026]** WhisperSplat: Lossless Steganography in 3D Gaussian Splatting [[Paper](https://icml.cc/virtual/2026/poster/64147)]
- **[ICLR 2026]** All That Glitters Is Not Gold: Key-Secured 3D Secrets within 3D Gaussian Splatting [[Paper](https://openreview.net/forum?id=CcxIDaTfLB)][[Code](https://github.com/RY-Paper/KeySS)]
- **[AAAI 2026]** Splats in Splats: Robust and Effective 3D Steganography towards Gaussian Splatting [[Paper](https://arxiv.org/abs/2412.03121)][[Code](https://github.com/insightlab-CG-3DV/splats-in-splats)]
- **[ICRA 2026]** Hide-in-Motion: Embedding Steganographic Copyright Information into 4D Gaussian Splatting Assets [[Paper](https://ieeexplore.ieee.org/abstract/document/11128285)][[Code](https://github.com/CUHK-AIM-Group/Hide-in-Motion)]
- **[ICLR 2025]** InstantSplamp: Fast and Generalizable Stenography Framework for Generative Gaussian Splatting [[Paper](https://openreview.net/forum?id=xvhV3LvYTc)][[Code](https://github.com/CUHK-AIM-Group/InstantSplamp)]
- **[ICLR 2025]** SecureGS: Boosting the Security and Fidelity of 3D Gaussian Splatting Steganography [[Paper](https://openreview.net/forum?id=H4FSx06FCZ)]
- **[SIGGRAPH 2025]** Hide A Bit: A Training-Free and High-Fidelity Steganography Method for 3D Gaussian Splatting Based on Bit Manipulation and RSA Encryption [[Paper](https://dl.acm.org/doi/full/10.1145/3721250.3743009)]
- **[KBS 2025]** StegaGaussian: High-fidelity Steganography for 3D Gaussian Splatting based on Frequency Decomposition [[Paper](https://www.sciencedirect.com/science/article/pii/S095070512501901X)][[Code](https://github.com/wangfeng70117/StegaGaussian)]
- **[ICASSP 2025]** ConcealGS: Concealing Invisible Copyright Information in 3D Gaussian Splatting [[Paper](https://ieeexplore.ieee.org/abstract/document/10890299)][[Code](https://github.com/zxk1212/ConcealGS)]
- **[NeurIPS 2024]** GS-Hider: Hiding Messages into 3D Gaussian Splatting [[Paper](https://openreview.net/forum?id=3XLQp2Xx3J&noteId=pVxlxrI17Y)][[Code](https://github.com/xuanyuzhang21/GS-Hider)]

### Tampering Localization
- **[AAAI 2026]** GS-Checker: Tampering Localization for 3D Gaussian Splatting [[Paper](https://arxiv.org/abs/2511.20354)][[Code](https://github.com/haolianghan/GS-Checker)]

### Traceability and Provenance
- **[arXiv 2026]** Who Generated This 3D Asset? Learning Source Attribution for Generative 3D Models [[Paper](https://arxiv.org/abs/2605.18132)]
- **[ICML 2026]** GaussTrace: Provenance Analysis of 3D Gaussian Splatting Models with Evidence-based LLM Reasoning [[Paper](https://openreview.net/forum?id=h9g5j4JFv8)]

### Editing Safeguard
- **[arXiv 2026]** GuardMarkGS: Unified Ownership Tracing and Edit Deterrence for 3D Gaussian Splatting [[Paper](https://arxiv.org/abs/2605.12919)]
- **[ICML 2026]** AdLift: Lifting Adversarial Perturbations to Safeguard 3D Gaussian Splatting Assets Against Instruction-Driven Editing [[Paper](https://arxiv.org/abs/2512.07247)]
- **[NeurIPS 2025]** DEGauss: Defending Against Malicious 3D Editing for Gaussian Splatting [[Paper](https://openreview.net/forum?id=Lm4VIXVIuy)]

## Model-level Protection

- **[arXiv 2026]** 3DEditSafe: Defending 3D Editing Pipelines from Unsafe Generation [[Paper](https://arxiv.org/abs/2605.15398)]
- **[arXiv 2026]** Immunizing 3D Gaussian Generative Models Against Unauthorized Fine-Tuning via Attribute-Space Traps [[Paper](https://arxiv.org/abs/2604.09688)]


## Citation

If you find this repository useful, please consider citing our survey:

```
@article{zhao2026intellectual,
  title={Intellectual Property Protection for 3D Gaussian Splatting Assets: A Survey},
  author={Zhao, Longjie and Hong, Ziming and Huang, Jiaxin and Chen, Runnan and Gong, Mingming and Liu, Tongliang},
  journal={arXiv preprint arXiv:2602.03878},
  year={2026}
}
```
