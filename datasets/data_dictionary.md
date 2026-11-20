# Data Dictionary

## Overview

This document describes the primary variables contained in the processed analytical dataset `input22mod01.csv`, which was derived from the 2022 National Household Travel Survey (NHTS) and used in the PioGraph-EcoML framework for transportation mode-choice prediction.

---

## Target Variable

| Variable | Description |
|-----------|-------------|
| TRPTRANS | Transportation mode choice (target variable used for classification) |

---

## Household Characteristics

| Variable | Description |
|-----------|-------------|
| HHSIZE | Total number of persons in the household |
| HHFAMINC | Household family income category |
| HHVEHCNT | Number of vehicles available in the household |
| HHACCCNT | Number of household members with access to vehicles |
| DRVRCNT | Number of licensed drivers in the household |
| HOMEOWN | Housing ownership status |

---

## Demographic Characteristics

| Variable | Description |
|-----------|-------------|
| R_AGE | Age of respondent |
| R_SEX | Respondent sex category |
| EDUC | Educational attainment level |
| WORKER | Employment status indicator |

---

## Travel Characteristics

| Variable | Description |
|-----------|-------------|
| TRPMILES | Trip distance (miles) |
| TRVLCMIN | Trip travel duration (minutes) |
| STRTTIME | Trip start time |
| ENDTIME | Trip end time |
| WHYTRP1S | Primary trip purpose |
| TDWKND | Weekend/weekday travel indicator |

---

## Geographic and Environmental Characteristics

| Variable | Description |
|-----------|-------------|
| URBRUR | Urban-rural classification |
| CENSUS_D | Census division identifier |
| HH_CBSA | Metropolitan statistical area indicator |

---

## Transportation Attributes

| Variable | Description |
|-----------|-------------|
| VEHOWNED | Vehicle ownership indicator |
| DRVR_FLG | Driver availability indicator |
| TRIPPURP | Consolidated trip-purpose category |

---

## Data Source

National Household Travel Survey (NHTS) 2022

Provider:
U.S. Federal Highway Administration (FHWA)

Official Website:
https://nhts.ornl.gov/

---
**Dataset Summary**

Source Dataset	NHTS 2022
Provider	FHWA
Records	31,074
Variables	21
File Name	input22mod01.csv
Application	Transportation Mode Choice Prediction

## Notes

1. Variable names correspond to the processed analytical dataset used in the PioGraph-EcoML study.
2. Some variables were transformed, encoded, consolidated, or reformatted during preprocessing to support econometric, machine-learning, and deep-learning analyses.
3. Refer to the manuscript methodology and reproducibility documentation for detailed information regarding preprocessing, feature preparation, and model development procedures.
4. The final analytical dataset contains 31,074 observations and 21 variables used throughout the experimental evaluation process.

---

## Citation

National Household Travel Survey (NHTS) 2022, U.S. Federal Highway Administration (FHWA).

PioGraph-EcoML Repository, Insights Solutions.
