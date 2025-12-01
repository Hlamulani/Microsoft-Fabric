# Notebooks Directory

This directory contains Microsoft Fabric notebooks (in Jupyter `.ipynb` format) for the diabetes classification project.

## Files
### `Train and compare models.ipynb`
Complete end-to-end workflow developed in Microsoft Fabric:

**Sections:**
1. **Data Ingestion** - Load diabetes dataset from Azure Open Datasets
2. **Data Exploration** - Initial analysis and visualization
3. **Data Preparation** - Using Fabric's Data Wrangler for transformations
4. **Feature Engineering** - Creating binary `Risk` column from continuous `Y` values
5. **AutoML Experiment** - Automated machine learning training
6. **Model Comparison** - Setup for manual model training comparison

## Usage
- Open in Microsoft Fabric for full interactive capabilities
- Can also be viewed in GitHub's built-in notebook viewer
- Run cells sequentially to reproduce results

## Note
These notebooks were developed specifically for Microsoft Fabric and leverage Fabric-specific features like Data Wrangler and integrated AutoML.
