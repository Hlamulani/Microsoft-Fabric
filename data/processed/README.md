# Processed Data Directory

Contains information about the cleaned and transformed datasets used for modeling.

## Source Data
**Dataset:** Diabetes dataset from Azure Open Datasets
**Original Source:** MLSamples container
**Format:** Parquet files
**Access:** Anonymous blob storage access

## Data Processing Steps
1. **Ingestion:** Loaded via PySpark from Azure Blob Storage
2. **Conversion:** Spark DataFrame to Pandas DataFrame
3. **Transformation:** Created binary `Risk` column using threshold (211.5)
4. **Cleaning:** No missing values in final dataset

## Final Dataset Structure
- **Rows:** 442 (patients)
- **Columns:** 12 (11 features + 1 target)
- **Features:** AGE, SEX, BMI, BP, S1, S2, S3, S4, S5, S6, Y
- **Target:** Risk (binary: 0=Low, 1=High)

## Data Characteristics
- All numeric features
- No missing values
- Approximately balanced for binary classification (25%/75%)
- Ready for machine learning algorithms

## Note
Due to data size and licensing, actual data files are not stored in this repository. The notebook contains code to download and process the data from the original source.
