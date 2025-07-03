# Cancer Diagnosis Using PCA and Feature Analysis

This project analyzes a dataset of cancer patient records to explore which features best differentiate malignant from benign tumors. It uses exploratory data analysis, statistical comparisons, and dimensionality reduction (PCA) to gain insights into patterns that support diagnostic predictions.

## Objectives
*1. Feature Distribution Analysis.*

- Visualize and compare distributions of diagnostic features across malignant and benign tumors using histograms and boxplots.

- Use statistical measures to identify the top 3 features with the strongest class separation.

*2. Dimensionality Reduction with PCA.*

- Apply PCA to the high-dimensional data to turn it into 2D.

- Visualize clusters and interpret patterns between cancer types in reduced dimensions.

## Dataset
The dataset is sourced from UCI’s Breast Cancer Wisconsin dataset. It includes:

- 30 real-valued features per patient (radius, texture, area, smoothness).

- Diagnosis label: M = malignant, B = benign.

## Technologies Used
- Python

- Pandas

- NumPy

- Matplotlib / Seaborn

- Scikit-learn

## Results
- Found 3 features radius mean, area mean and perimeter mean that strongly distinguish between malignant and benign samples.

- PCA revealed that malignant and benign tumors form largely distinct clusters in 2D space, suggesting effective separation with fewer dimensions.


