# Models Directory

This directory is intended for storing trained machine learning models from the diabetes classification project.

## Expected Contents
- Trained model files (.pkl, .joblib, or .onnx format)
- Model metadata and configuration files
- Model performance reports
- Deployment artifacts

## Current Status
**Note:** As this project focuses on the Microsoft Fabric workflow and AutoML experimentation, trained model files are currently stored within Fabric's model registry rather than in this repository.

## Model Information
**Best AutoML Model:**
- **Algorithm:** [To be determined from AutoML results]
- **Accuracy:** 87.7%
- **F1 Score:** 87.4%
- **Training Data:** 442 samples with 11 features

## Model Types Explored
1. **AutoML Selected Model** - Best performing algorithm chosen automatically
2. **Logistic Regression** (Planned) - Baseline classification model
3. **Random Forest** (Planned) - Ensemble method for comparison

## Exporting Models from Microsoft Fabric
To save models locally for this repository:
```python
# Example code for model export
import joblib
from sklearn.ensemble import RandomForestClassifier

# Train and save a model
model = RandomForestClassifier()
model.fit(X_train, y_train)
joblib.dump(model, 'models/diabetes_rf_model.pkl')
