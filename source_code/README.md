# Source Code

## Overview

This directory contains the implementation resources supporting the PioGraph\-EcoML framework.

PioGraph\-EcoML is a graph\-based analytical framework that integrates econometric methods, machine\-learning algorithms, deep\-learning architectures, and statistical validation techniques to improve transportation mode\-choice prediction and interpretability.

The framework is organized around two complementary methodologies:

- Integrated Modeling Improvement Methodology (I\-MIM)
- Continuous Modeling Improvement Methodology (C\-MIM)

Together, these methodologies support model development, evaluation, comparison, and continuous performance improvement.

---

## I\-MIM Framework

The Integrated Modeling Improvement Methodology (I\-MIM) focuses on improving predictive performance through structured model enhancement while maintaining interpretability.

The workflow incorporates:

- Logistic Regression baseline models
- Random Forest models
- Balanced Random Forest models
- Class\-balancing techniques
- Feature engineering procedures
- Recursive Feature Elimination (RFE)
- Ensemble\-learning approaches
- Performance optimization strategies

The objective of I\-MIM is to identify interpretable model configurations that maximize predictive performance while retaining economic and behavioral insights.

---

## C\-MIM Framework

The Continuous Modeling Improvement Methodology (C\-MIM) focuses on progressive enhancement of deep\-learning architectures through sequential model refinement.

The workflow incorporates:

- Deep Neural Networks (DNN)
- Convolutional Neural Networks (CNN)
- Recurrent Neural Networks (RNN)
- Long Short\-Term Memory (LSTM) networks
- Hybrid CNN\-LSTM architectures

The objective of C\-MIM is to continuously improve predictive performance by evaluating increasingly sophisticated neural\-network configurations and integrated architectures.

---

## Data Processing Workflow

The analytical workflow includes:

1. Data acquisition.
2. Data transformation and preparation.
3. Feature engineering and selection.
4. Model development and training.
5. Model evaluation and comparison.
6. Statistical validation.
7. Result interpretation and reporting.

The workflows operate using the processed analytical dataset derived from the 2022 National Household Travel Survey (NHTS).

---

## Experimental Environment

Primary software technologies used in this study include:

- Python
- Scikit\-learn
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1\-Score
- Area Under the Curve (AUC)
- Confusion Matrices
- Statistical significance testing

Performance comparisons between competing models were validated using McNemar's statistical test.

---

## Statistical Validation

The framework applies McNemar's test to evaluate whether observed differences in classification performance are statistically significant.

This approach supports rigorous comparison across econometric, machine\-learning, deep\-learning, and hybrid model configurations.

---

## Reproducibility

The implementation workflow was designed to support transparent and reproducible experimentation.

Dataset information, preprocessing procedures, experimental configuration, model evaluation methodology, and statistical validation procedures are documented throughout this repository and in the associated PioGraph\-EcoML publication.

---

## Repository Structure

source\_code/

- Data preprocessing workflows
- Feature engineering procedures
- Model development resources
- Evaluation workflows
- Validation procedures
- Visualization utilities

For complete experimental details, refer to the documentation provided in the docs directory and the associated research publication.

