# Rethinking Rotation in Self-Supervised Contrastive Learning: Adaptive Positive or Negative Data Augmentation

This is the PyTorch impelementation of our paper.

Our method comprises two major steps:

1. Run sampling of RAI whose rotation is treated as positive.
2. Run PNDA for contrastive learning (MoCo v2, SimCLR).

The codes and their details for each step are stored in a sub-directory with the corresponding name `RAI_SAMPLING`, `PNDA_SIMCLR`, `PNDA_MOCO`.

The RAI sampling results used in the experiment are stored in `RAI_results`.
Therefore, you can start from either step.

## Datasets 
Please make `data` folder here. 
Please download following datasets to `data`.
* [CIFAR100](https://drive.google.com/file/d/1FRi1K1ZQ-OCgIhMROwjYAt_m_K44Q9ea/view?usp=sharing)
* [Tiny ImageNet](https://drive.google.com/file/d/1b846FVuOPpZbOnKaiFd2OL4MZntbiiPr/view?usp=sharing)