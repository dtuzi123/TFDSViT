# TFDSViT

# Task-Free Dynamic Sparse Vision Transformer for Continual Learning

>📋 This is the implementation of Task-Free Dynamic Sparse Vision Transformer for Continual Learning

>📋 Accepted by AAAI 2024

# Title : Task-Free Dynamic Sparse Vision Transformer for Continual Learning

# Paper link : 



# Abstract

Vision Transformers (ViTs) represent self-attention-based network backbones that have proved to be efficient in many individual tasks, but which have not been explored in the context of Task-Free Continual Learning (TFCL) so far. Most existing ViT-based approaches for Continual Learning (CL) are relying on task information. In this study, we explore the advantages of the ViT in a more challenging CL scenario where the task boundaries are unavailable during training. To address this learning paradigm, we propose the Task-Free Dynamic Sparse Vision Transformer (TFDSViT), which can dynamically build new sparse experts, where each expert leverages sparsity to allocate the model's capacity for capturing different information categories over time. To avoid forgetting and ensure efficiency in reusing the previously learned knowledge in subsequent learning, we propose a new dynamic dual attention mechanism consisting of the Sparse Attention (SA') and Knowledge Transfer Attention (KTA) modules. The SA' refrains from updating some previously learned attention blocks in order to preserve prior knowledge. The KTA uses and regulates the information flow of all previously learned experts for learning new patterns. The proposed dual attention mechanism can simultaneously relieve forgetting and promote knowledge transfer for a dynamic expansion model in a task-free manner. In addition, we propose an energy-based dynamic expansion mechanism using the energy as a measure of novelty for the incoming samples which provides appropriate expansion signals leading to a compact network architecture for TFDSViT. Extensive empirical studies demonstrate the effectiveness of TFDSViT.

# Environment

1. Tensorflow 2.1
2. Python 3.6

# Training and evaluation

>📋 Python xxx.py, the model will be automatically trained and then report the results after the training.

>📋 Different parameter settings of OCM would lead different results and we also provide different settings used in our experiments.

# BibTex
>📋 If you use our code, please cite our paper as:

@inproceedings{ye2022continual,
  title={Continual variational autoencoder learning via online cooperative memorization},
  author={Ye, Fei and Bors, Adrian G},
  booktitle={European Conference on Computer Vision},
  pages={531--549},
  year={2022},
  organization={Springer}
}


