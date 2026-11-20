# Academic-research


This repository contains a collection of academic research projects, empirical studies, and technical reports conducted during my studiesL.

Research Reports

1. Coordinate-wise Adaptive Learning Rate Schemes: A Comparative Empirical Study of Adam, SignSGD, Lion, and AdaHessian

Institution: École Polytechnique Fédérale de Lausanne (EPFL)
Authors: Alice Chemali, Andrea Trugenberger, Ibrahim Khribch
Field: Machine Learning, Numerical Optimization
Year: 2026
Overview

This empirical study compares four coordinate-wise adaptive optimization algorithms—Adam, SignSGD with momentum, Lion, and AdaHessian—using convolutional neural networks trained on MNIST and CIFAR-10.

The experiments investigate convergence behavior, numerical stability, and sensitivity to batch size across different training configurations.

Methodology

Comparative evaluation of four optimization algorithms.

Experiments on MNIST and CIFAR-10 using convolutional neural networks.

Batch sizes of 32, 128, 512, and 1024.

Three independent random seeds per configuration.

Evaluation of training convergence, classification accuracy, and numerical stability.

Main Findings

The results indicate that greater algorithmic complexity and richer gradient information do not necessarily improve practical optimization performance.

SignSGD with momentum exhibits the greatest robustness across the tested configurations, while AdaHessian suffers from substantial numerical instability, particularly on MNIST.

These findings emphasize the importance of empirical robustness alongside theoretical properties when evaluating optimization methods.
