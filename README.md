# Multimodality in Robotics Explained

This repository contains the companion Jupyter notebook for the video ["Multimodality in Robotics"](https://www.youtube.com/watch?v=6oZe_tKE3YA) that explores different approaches to handling multimodality in robotics: predicting continuous actions when multiple correct actions exist.

## Overview

The notebook demonstrates several approaches to handling multimodal distributions in robotics:

1. Simple MSE regression and its limitations
2. MAE regression and comparison with MSE
3. Target tokenization and classification
4. Diffusion Policy
5. Flow Matching Policy

Each approach is implemented with clear code examples and visualizations to help understand the concepts.

## Getting Started

### Running the Notebook locally

1. Clone this repository:
```bash
git clone https://github.com/IliaLarchenko/robotics_multimodality_explained
cd robotics_multimodality_explained
```

2. Install the required packages:
```bash
pip install -r requirements.txt
```

3. Open and run the notebook:
```bash
jupyter notebook multimodality_analysis.ipynb
```

### Running on Kaggle

The notebook is also available on Kaggle, just click the link below:
[Kaggle Notebook Version](https://www.kaggle.com/code/ilialar/multimodality-explained)


## References

### Papers
- [ACT: Learning Fine-Grained Bimanual Manipulation with Low-Cost Hardware](https://arxiv.org/abs/2304.13705)
- [Diffusion Policy: Visuomotor Policy Learning via Action Diffusion](https://arxiv.org/abs/2303.04137)
- [Behavior Transformers: Cloning k Modes with One Stone](https://arxiv.org/abs/2206.11251)
- [VQ-BET: Behavior Generation with Latent Actions](https://arxiv.org/abs/2403.03181)
- [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239)
- [DDIM: Denoising Diffusion Implicit Models](https://arxiv.org/abs/2010.02502)
- [Flow Matching for Generative Modeling](https://arxiv.org/abs/2210.02747)

### Additional Resources
- [MIT Course on Diffusion & Flow Matching (SDE perspective)](https://diffusion.csail.mit.edu/)
- [DOT-Policy Implementation](https://github.com/IliaLarchenko/dot_policy)


## Author

Ilia Larchenko
- GitHub: [@IliaLarchenko](https://github.com/IliaLarchenko)
- Kaggle: [@ilialar](https://www.kaggle.com/ilialar)
- YouTube: [@IliaLarchenko](https://www.youtube.com/@IliaLarchenko)
- Linktree: [@IliaLarchenko](https://linktr.ee/IliaLarchenko)
