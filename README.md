# Microsoft Fabric - Diabetes Risk Classification

## Project Overview
Healthcare analytics project developed in Microsoft Fabric for predicting diabetes risk from patient biomarkers. This end-to-end workflow demonstrates Fabric's machine learning capabilities including data preparation, automated feature engineering, and model training.

## Key Results
- **AutoML Accuracy:** 87.7%
- **AutoML F1 Score:** 87.4%
- **Dataset:** 442 patient samples with 11 biomarkers
- **Target:** Binary classification (High/Low Risk)
- **High Risk Patients:** ~25% of dataset

## Project Structure
Microsoft-Fabric/
├── notebooks/
│   └── Train and compare models.ipynb
├── experiments/
│   ├── automl_results.md
│   └── README.md
├── data/
│   ├── processed/
│   │   └── README.md
│   └── README.md
├── models/
│   └── README.md
├── README.md
└── requirements.txt
