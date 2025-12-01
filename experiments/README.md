# Experiments Directory

Contains machine learning experiment results, metrics, and artifacts from the diabetes classification project.

## AutoML Experiment Results
**Run ID:** `amiable_nerve_ch4libnvp`
- **Accuracy:** 87.7%
- **F1 Score:** 87.4%
- **Log Loss:** 0.307
- **Status:** Completed
- **Duration:** ~66 seconds

## Dataset Information
- **Total Samples:** 442 patients
- **Features:** 11 medical biomarkers (AGE, SEX, BMI, BP, S1-S6)
- **Target Variable:** `Risk` (binary: 0=Low Risk, 1=High Risk)
- **Class Distribution:** ~25% High Risk, ~75% Low Risk

## Feature Engineering
- **Threshold:** 211.5 (75th percentile of original `Y` values)
- **Transformation:** `Risk = 1 if Y > 211.5 else 0`
- **Purpose:** Convert regression problem to binary classification

## Next Steps for Experimentation
1. Manual model training (Logistic Regression, Random Forest)
2. Feature importance analysis
3. Hyperparameter tuning
4. Cross-validation results
