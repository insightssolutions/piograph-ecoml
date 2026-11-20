# Results

## Overview

This directory contains the experimental results, performance summaries, statistical validation outputs, and supporting materials generated during the evaluation of the PioGraph\-EcoML framework.

The results support the comparison of the Integrated Modeling Improvement Methodology (I\-MIM) and the Continuous Modeling Improvement Methodology (C\-MIM) for transportation mode\-choice prediction.

---

## Included Results

The reported results are derived from experiments conducted using the processed NHTS 2022 analytical dataset (input22mod01.csv).

Key evaluation outputs include:

- Classification accuracy
- Precision
- Recall
- F1\-score
- Area Under the Curve (AUC)
- Confusion matrices
- Feature\-importance analysis
- Comparative model\-performance assessment
- Statistical significance testing

---

## I\-MIM Results

The I\-MIM framework evaluates a sequence of progressively enhanced machine\-learning models incorporating:

- Logistic Regression
- Random Forest
- Balanced Random Forest
- Ensemble Learning
- Feature Selection
- Class\-Balancing Techniques

The final I\-MIM configuration achieved the highest performance among the evaluated I\-MIM stages and served as the representative machine\-learning benchmark for framework comparison.

---

## C\-MIM Results

The C\-MIM framework evaluates progressively enhanced deep\-learning architectures including:

- Deep Neural Networks (DNN)
- Convolutional Neural Networks (CNN)
- Recurrent Neural Networks (RNN)
- Long Short\-Term Memory Networks (LSTM)
- Hybrid CNN\-LSTM Models

The final C\-MIM architecture demonstrated the strongest predictive performance among the evaluated deep\-learning configurations.

---

## Statistical Validation

Performance differences between competing model configurations were evaluated using McNemar's statistical test.

The statistical validation process was used to determine whether observed performance differences were statistically significant and to support objective comparison between I\-MIM and C\-MIM outcomes.

---

## Reproducibility

The experimental procedures used to generate these results are documented in:

- datasets/README.md
- source\_code/README.md
- docs/reproducibility.md

Researchers can reproduce the reported workflow using the dataset, documentation, and implementation procedures provided in this repository.

---

## Associated Study

PioGraph\-EcoML: A Novel Data\-Driven Graph\-Based Framework for Integrating Econometric Models and Machine Learning Algorithms.

