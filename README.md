# K-UniDet: Knowledge-Guided Contrastive Learning in a Unified Feature Space for Few-Shot Wheat Disease Detection

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-1.12+-orange)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Under%20Review-yellow)

</div>

## 📖 Introduction

This repository is the official implementation of **K-UniDet**, a knowledge-guided contrastive learning framework for few-shot wheat disease detection in remote sensing-based agricultural monitoring scenarios.

Few-shot wheat disease detection faces three core challenges in real field environments: **disease semantic ambiguity**, **cross-domain distribution shift**, and **data scarcity**. To address these issues, K-UniDet proposes:

- **SPM** (Semantic Prior Modeling): Constructs an inter-class visual-semantic knowledge matrix within a unified feature space via DINOv2, eliminating the heterogeneous semantic gap between base and novel disease classes.
- **KPCL** (Knowledge-Guided Prototype Contrastive Learning): Incorporates a dynamic prototype memory bank and hard negative sampling strategy to enhance discriminability among visually similar disease categories.
- **DDAM** (Domain-Aware Data Augmentation Mechanism): Retrieves target-domain backgrounds and performs semantically guided diffusion synthesis to alleviate novel-class overfitting under few-shot conditions.

Experiments on the **WD-5** dataset demonstrate that K-UniDet achieves **52.58% AP** under the 20-shot setting, substantially outperforming existing few-shot detection methods.

## 📊 Dataset: WD-5

WD-5 is a large-scale benchmark dataset for few-shot wheat disease detection, comprising **33,114 high-resolution images** and **61,020 instance bounding boxes** across five disease categories: Rust, Smut, Blight, Powdery Mildew, and Scab.

The test set is now publicly available:

> 📥 **[Download WD-5 Test Set (Google Drive)](https://drive.google.com/file/d/12bN2vdeIRi_qb7azZgbzMOGjlz2jf-em/view?usp=sharing)**

## 🚀 Code

The full training and inference code will be released upon journal acceptance. Please star ⭐ this repository to stay updated.

## 📝 Citation

If you find this work useful in your research, please consider citing:

```bibtex
@article{yang2025kunidet,
  title={K-UniDet: Knowledge-Guided Contrastive Learning in a Unified Feature Space for Few-Shot Wheat Disease Detection},
  author={Yang, Zihao and Bao, Wenxia and Fang, Yue and Shao, Pengpeng and Liang, Dong and Yang, Xianjun},
  journal={Under Review},
  year={2025}
}
```

## 📬 Contact

For questions, please contact: **bwxia@ahu.edu.cn** (Corresponding Author: Wenxia Bao)
