# Transfer Learning Experiments using Resnet

This repository contains all code related to experiments conducted for comparing a fine-tuned ResNet-18 model with a ResNEt-18 model trained from scratch.

This repository contains the following two python files:
1. `resnet_comparison_v1.py` contains the code related to the comparison of performance between a ResNet-50 model trained on the CIFAR-10 dataset, shrunk to a ResNet-18 model, and fine-tuned on the CIFAR-100 dataset and a purely 18-layered ResNet trained on CIFAR-100 for the same number of epochs.

2. `resnet_comparison_v2.py` contains the code related to the comparison of performance between a fine-tuned ResNet-18 model and a purely 18-layered ResNet trained from scratch. This experiment incorporates the concepts of patience and few shot learning.

## Running Instructions:

To run the first set of experiments, run the following command in the terminal:

> python3 resnet_comparison_v1.py

To run the next set of experiments, run the following command:

> python3 resnet_comparison_v3.py

