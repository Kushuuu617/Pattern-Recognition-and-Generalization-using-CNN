# Pattern-Recognition-and-Generalization-using-CNN
University project under the course Machine Learning (BITS F464) at BITS Pilani KK Birla Goa campus.

1.1 Problem Statement : Pattern Recognization and Generalization on ARC Dataset using Convolutional Neural Networks

1.2 Hypothesis : Increasing the number of layers in a convolutional neural network can lead to higher training errors in small and complex datasets due to over-parameterization or overfitting regularization effects.

Short Summary

The goal is to study how convolutional neural networks (CNNs) learn to recognize patterns in data and generalize to unseen examples. This involves analyzing the impact of model complexity (number of layers) on the training and generalization performance. This hypothesis suggests that deeper networks might struggle to optimize effectively or fail to fit smaller datasets, whereas shallower networks might perform better due to their simplicity. The models used for this were

2 Layered Convolutional Neural Network (Achieved a validation error of ~0.06)
ResNet18 (Achieved a validation error of ~4)
The results support the hypothesis that deeper networks can suffer from overparameterization or regularization effects, especially when the dataset is small and complex. The shallow CNN, being less complex, could better fit the training data.

ARC DATASET : https://www.kaggle.com/competitions/abstraction-and-reasoning-challenge
