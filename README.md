# ml-statistical-measures

# ML Assignment 1: Statistical Measures and Data Analysis

This repository contains the code, dataset, and analysis for the ML Assignment focusing on exploratory data analysis (EDA), outlier detection, and feature transformations. The code demonstrates various statistical methods and visualization techniques to prepare the dataset for further analysis or machine learning modeling.

---

## Repository Structure

- **`ml_assignment_1_statistical_measures.py`**: Python script with the complete code for the assignment.
- **`house_price.csv`**: Dataset used for analysis (uploaded as part of the repository).
- **`screenshots/`**: Directory containing screenshots of the code execution and outputs in `.pdf` format.

---

## Objective

1. **Perform Basic EDA**:
   - Understand the structure and characteristics of the dataset.
   - Identify and analyze potential data issues like null values and anomalies.

2. **Outlier Detection and Handling**:
   - Detect outliers using multiple statistical methods:
     - Mean-Standard Deviation
     - Percentile
     - Interquartile Range (IQR)
     - Z-Score
   - Handle outliers with:
     - Trimming
     - Capping
     - Median Imputation

3. **Feature Transformations**:
   - Apply transformations (e.g., log, square root, Box-Cox) to address skewness and normalize data distribution.
   - Assess skewness and kurtosis before and after transformations.

4. **Correlation Analysis and Visualizations**:
   - Calculate correlation between numerical variables.
   - Visualize correlations using heatmaps and scatter plots.

5. **Determine Best Methods**:
   - Compare the effectiveness of outlier detection and handling methods.
   - Identify suitable transformations for improved data normalization.

---

## Key Findings

- **Outlier Handling**:
  - The **IQR method** combined with **capping** was most effective in managing outliers while preserving data integrity.
  
- **Feature Transformation**:
  - Transformations like **Log Transformation** and **Yeo-Johnson** significantly reduced skewness and improved normality in the dataset.

- **EDA Observations**:
  - Columns like `bath` and `size` contained unreasonable values (e.g., up to 40 bathrooms or 43 bedrooms), requiring further cleaning and standardization.

---

## Visualizations

1. **Box Plots**:
   - Compared the effects of different outlier handling techniques.
   
2. **Histograms**:
   - Evaluated data distribution before and after feature transformations.

3. **Correlation Heatmap**:
   - Showed relationships between numerical variables to aid feature selection.

4. **Scatter Plots**:
   - Visualized pairwise correlations among key variables.

---

## Dependencies

To run the code in this repository, ensure the following Python libraries are installed:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`

