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


## Technologies
- **Microsoft Fabric** - Primary development platform
- **PySpark** - Data processing and ingestion
- **Data Wrangler** - Interactive data transformation
- **AutoML** - Automated machine learning
- **Scikit-learn** - Traditional ML algorithms
- **Jupyter Notebooks** - Interactive coding environment (.ipynb format)

## Getting Started
1. Open the notebook in Microsoft Fabric
2. Run cells sequentially to reproduce the workflow
3. Explore Data Wrangler transformations
4. Review AutoML experiment results

## Notebook Contents
- Data ingestion from Azure Open Datasets
- Data exploration and visualization
- Feature engineering with Data Wrangler
- Binary classification label creation
- AutoML model training and evaluation
- Model comparison setup

## License
This project is for educational/demonstration purposes.
