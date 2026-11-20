# Datasets
This folder contains the datasets, data dictionaries, preprocessing notes, and metadata used in the study.
Data access restrictions and licensing information are documented where applicable.

**Overview
**
This directory contains the dataset resources supporting the PioGraph-EcoML framework presented in the associated research study.
The analytical dataset used in this research was derived from the 2022 National Household Travel Survey (NHTS), a nationally representative travel survey conducted by the U.S. Federal Highway Administration (FHWA). The dataset was prepared to support transportation mode-choice prediction using econometric, machine-learning, deep-learning, and graph-based analytical approaches.


**Source Dataset
**Dataset Name: National Household Travel Survey (NHTS) 2022
Provider: U.S. Federal Highway Administration (FHWA)
Official Source: https://nhts.ornl.gov/
The NHTS provides detailed information regarding travel behavior, household characteristics, demographic factors, vehicle ownership, trip attributes, and transportation choices across the United States.


**Processed Analytical Dataset
**File Name: input22mod01.csv
The file input22mod01.csv represents the processed analytical dataset used throughout the PioGraph-EcoML experiments.
Dataset Characteristics

- Total observations: 31,074
- Total variables: 21
- Prediction task: Transportation mode-choice classification
- Application domain: Transportation analytics and intelligent mobility modeling


Data Transformation
The original NHTS 2022 data underwent a structured transformation process to prepare the dataset for econometric and machine-learning analysis.
The transformation workflow included:

1. Selection of transportation mode-choice relevant records.
2. Data quality assessment and removal of incomplete or inconsistent observations.
3. Variable selection based on transportation, household, demographic, and travel-related attributes.
4. Preparation and encoding of categorical variables for analytical modeling.
5. Feature preparation and formatting to support the Integrated Modeling Improvement Methodology (I-MIM) and the Continuous Modeling Improvement Methodology (C-MIM).
6. Construction of the final analytical dataset used for model training, validation, testing, and statistical evaluation.
These procedures were performed to ensure consistency, analytical validity, and reproducibility across all stages of the PioGraph-EcoML framework.


Variables
The final dataset contains variables representing:

- Demographic characteristics
- Household characteristics
- Vehicle ownership indicators
- Driver availability indicators
- Travel distance measures
- Travel duration measures
- Temporal travel characteristics
- Transportation behavior variables
- Mode-choice outcomes


Reproducibility
Researchers can obtain the original NHTS 2022 dataset directly from the official NHTS website and reproduce the analytical workflow using the preprocessing, modeling, evaluation, and statistical validation procedures documented in this repository and the associated manuscript.


Citation
When using this dataset description in academic work, please cite the associated PioGraph-EcoML publication and the original National Household Travel Survey (NHTS) data source.
National Household Travel Survey (NHTS), U.S. Federal Highway Administration (FHWA), https://nhts.ornl.gov/
