# Reproducibility Guide

## Overview

This repository supports the reproducibility of the PioGraph\-EcoML framework described in the associated research publication.

PioGraph\-EcoML integrates econometric methods, machine\-learning algorithms, deep\-learning architectures, and graph\-based modeling concepts to improve transportation mode\-choice prediction and interpretability.

This document outlines the workflow used to generate the reported results and provides guidance for researchers seeking to reproduce the experiments.

---

# Data Source

## Original Dataset

Dataset: National Household Travel Survey (NHTS) 2022

Provider: U.S. Federal Highway Administration (FHWA)

Source: [https://nhts.ornl.gov/](https://nhts.ornl.gov/)

---

# Analytical Dataset

Processed Dataset: input22mod01.csv

The analytical dataset was derived from the NHTS 2022 survey and prepared for transportation mode\-choice prediction experiments.

Dataset Characteristics:

- 31,074 observations
- 21 variables
- Transportation mode\-choice classification task

---

# Reproduction Workflow

## Step 1: Data Acquisition

Obtain the original National Household Travel Survey (NHTS) 2022 dataset from the official NHTS website.

## Step 2: Data Transformation

Apply the preprocessing and transformation procedures described in the manuscript, including:

- Data filtering
- Data quality assessment
- Removal of incomplete or inconsistent records
- Variable selection
- Categorical variable preparation
- Feature preparation
- Construction of the analytical dataset

The resulting processed dataset is represented by:

input22mod01.csv

## Step 3: I\-MIM Framework Evaluation

Execute the Integrated Modeling Improvement Methodology (I\-MIM) workflow.

The I\-MIM framework evaluates a sequence of model\-development stages that include:

- Baseline Logistic Regression
- Random Forest
- Class balancing techniques
- Feature engineering approaches
- Ensemble learning methods
- Feature selection procedures
- Performance evaluation

Performance metrics include:

- Accuracy
- Precision
- Recall
- F1 Score
- AUC

## Step 4: C\-MIM Framework Evaluation

Execute the Continuous Modeling Improvement Methodology (C\-MIM) workflow.

The C\-MIM framework evaluates progressively enhanced architectures including:

- Deep Neural Networks (DNN)
- Convolutional Neural Networks (CNN)
- Recurrent Neural Networks (RNN)
- Long Short\-Term Memory (LSTM) models
- Hybrid CNN\-LSTM architectures

Model improvements are assessed across sequential development stages.

Performance metrics include:

- Accuracy
- Precision
- Recall
- F1 Score
- AUC

---

# Experimental Configuration

Software Environment:

- Python
- Scikit\-learn
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn

Dataset Partitioning:

- Training Set: 60%
- Validation Set: 20%
- Test Set: 20%

Cross\-Validation:

- Stratified K\-Fold Cross Validation
- k = 5

Cross\-validation is applied only to the training subset. Validation and testing subsets remain independent and are used exclusively for model selection and final evaluation.

Deep Learning Configuration:

- Optimizer: Adam
- Loss Function: Categorical Cross\-Entropy
- Batch Size: 32
- Epochs: 50
- Early Stopping: Enabled

---

# Statistical Validation

Performance differences between models are evaluated using McNemar's statistical test.

The test is used to determine whether observed differences in classification performance are statistically significant.

Significance threshold:

α = 0.05

---

# Results Reproduction

Researchers should be able to reproduce:

- Performance tables
- Accuracy comparisons
- Evaluation metrics
- Feature importance analyses
- McNemar statistical validation results
- Framework comparison results

subject to the same dataset, preprocessing procedures, model configurations, and evaluation methodology described in the manuscript.

---

# Repository Structure

datasets/

- Dataset documentation
- Processed analytical dataset
- Data dictionary

source\_code/

- Data preprocessing
- Model development
- Evaluation workflows

models/

- Trained model artifacts and configurations

results/

- Figures
- Tables
- Statistical validation outputs

docs/

- Reproducibility documentation

---

# Citation

If this repository contributes to academic research, please cite the associated PioGraph\-EcoML publication together with the original National Household Travel Survey (NHTS) dataset source.

National Household Travel Survey (NHTS), U.S. Federal Highway Administration (FHWA), [https://nhts.ornl.gov/](https://nhts.ornl.gov/)

