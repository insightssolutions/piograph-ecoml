# Models

## Overview

This directory is reserved for model artifacts, configurations, and supporting resources associated with the PioGraph\-EcoML framework.

The study evaluates two complementary modeling methodologies:

- Integrated Modeling Improvement Methodology (I\-MIM)
- Continuous Modeling Improvement Methodology (C\-MIM)

---

## I\-MIM Models

The I\-MIM framework evaluates interpretable econometric and machine\-learning approaches, including:

- Logistic Regression
- Random Forest
- Balanced Random Forest
- Ensemble Learning Models
- Recursive Feature Elimination (RFE) enhanced models
- Class\-balanced learning approaches

These models support feature\-importance analysis and economic interpretation.

---

## C\-MIM Models

The C\-MIM framework evaluates progressive deep\-learning architectures, including:

- Deep Neural Networks (DNN)
- Convolutional Neural Networks (CNN)
- Recurrent Neural Networks (RNN)
- Long Short\-Term Memory Networks (LSTM)
- Hybrid CNN\-LSTM Architectures

These models support continuous performance improvement through sequential architectural enhancement.

---

## Model Configuration

The experimental configurations used in the study are documented in the manuscript and repository documentation.

Key settings include:

- Stratified K\-Fold Cross Validation (k = 5)
- Training/Validation/Test Split (60% / 20% / 20%)
- Adam Optimizer
- Categorical Cross\-Entropy Loss
- Early Stopping Regularization
- Batch Size: 32
- Maximum Epochs: 50

---

## Reproducibility

The repository provides the dataset documentation, workflow descriptions, and reproducibility guidance required to recreate the model\-development process reported in the PioGraph\-EcoML study.

Model artifacts may be added in future repository releases as the framework evolves.

