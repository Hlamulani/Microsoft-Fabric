# Microsoft-Fabric Diabetes Classification Project

## Project Overview
End-to-end healthcare analytics project using Microsoft Fabric to predict diabetes risk from patient biomarkers.

## Key Features
- **Data Ingestion**: Loaded diabetes dataset from Azure Open Datasets
- **Data Preparation**: Used Data Wrangler to create binary `Risk` column (threshold: 211.5)
- **AutoML Experiment**: Achieved 87.7% accuracy automatically
- **Model Comparison**: Ready for manual Logistic Regression vs Random Forest comparison

## Files
- `Train and compare models.ipynb` - Complete Jupyter notebook with all steps

## Technologies Used
- Microsoft Fabric
- PySpark for data processing
- Scikit-learn for machine learning
- AutoML for automated model selection
- Data Wrangler for interactive data transformation

## Results
- AutoML Accuracy: **87.7%**
- AutoML F1 Score: **87.4%**
- High Risk Patients: **~25%** of dataset

## Getting Started
1. Open the notebook in Microsoft Fabric
2. Run cells sequentially
3. Explore Data Wrangler transformations
4. Review AutoML experiment results

## Next Steps
- Complete manual model training comparison
- Analyze feature importance
- Deploy best model as API
