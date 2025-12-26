# 📊 BigMart Sales Data Preprocessing & PCA Analysis

<div align="center">
A comprehensive Jupyter notebook for cleaning retail sales data, fixing inconsistencies, and applying Principal Component Analysis to reduce dimensionality and extract sales insights
</div>

---

### Problem
Retail sales datasets contain missing values, inconsistent categories, and outliers.  
High feature count makes analysis and modeling harder.  
Sales prediction suffers without clean data.

### Solution
A complete preprocessing pipeline in one Jupyter notebook.  
Includes EDA, cleaning, encoding, scaling, and PCA.  
Produces clear visual outputs for analysis and reporting.

### Idea
Reduce more than ten numerical and categorical features into a few principal components.  
Preserve most data variance.  
Prepare data for machine learning models.

---
### Project Graphs

**Key visualizations from the notebook—run it**
<p align="center">
  <img src="https://github.com/Basmala-ElKady/BigMart-Sales-Data-Preprocessing-PCA-Analysis/blob/main/Project%201/pca_plots/pca_2d_projection.png" alt="Graph 1" width="400" style="margin-right: 10px;"/>
  <img src="https://github.com/Basmala-ElKady/BigMart-Sales-Data-Preprocessing-PCA-Analysis/blob/main/Project%201/pca_plots/pca_3d_projection.png" alt="Graph 1" width="400" style="margin-right: 10px;"/>
</p>

---
### EDA Boxplots
**Outlier detection and distribution analysis for key numerical features:**

<p align="center">
  <img src="https://github.com/Basmala-ElKady/BigMart-Sales-Data-Preprocessing-PCA-Analysis/blob/main/Project%201/plots/boxplot_Item_MRP.png" alt="Boxplot Item MRP" width="300" style="margin-right: 10px;"/>
  <img src="https://github.com/Basmala-ElKady/BigMart-Sales-Data-Preprocessing-PCA-Analysis/blob/main/Project%201/plots/boxplot_Item_Outlet_Sales.png" alt="Boxplot Item Outlet Sales" width="300" style="margin-right: 10px;"/>
  <img src="https://github.com/Basmala-ElKady/BigMart-Sales-Data-Preprocessing-PCA-Analysis/blob/main/Project%201/plots/boxplot_Item_Visibility.png" alt="Boxplot Item Visibility" width="300"/>
</p>

<p align="center">
  <img src="https://github.com/Basmala-ElKady/BigMart-Sales-Data-Preprocessing-PCA-Analysis/blob/main/Project%201/plots/boxplot_Item_Weight.png" alt="Boxplot Item Weight" width="300" style="margin-right: 10px;"/>
  <img src="https://github.com/Basmala-ElKady/BigMart-Sales-Data-Preprocessing-PCA-Analysis/blob/main/Project%201/plots/boxplot_Outlet_Establishment_Year.png" alt="Boxplot Outlet Establishment Year" width="300"/>
</p>

---
### Data Cleaning Process
**Overview of cleaning steps: Impute missing weights by item type median, cap outliers , standardize categories. Below is an example before/after for Item_MRP; check other similar plots in `/Project 1/plots_before_after/`.**

<p align="center">
  <img src="https://github.com/Basmala-ElKady/BigMart-Sales-Data-Preprocessing-PCA-Analysis/blob/main/Project%201/plots_before_after/Item_MRP_before_after.png" alt="Pre-Cleaning: Item Weight Outliers" width="900" style="margin-right: 10px;"/>
  
</p>

*(Run the notebook to generate before/after comparisons; cleaned data exported as 'cleaned_data.csv'.)*

---
### Setup & Testing
1. Use Jupyter Notebook or VS Code to execute the notebook.
2. Load the dataset via `pd.read_csv('train2.csv')`.
3. Verify results: Inspect cleaned data with `df.info()`.

For the full notebook: [View Jupyter](https://github.com/Basmala-ElKady/BigMart-Sales-Data-Preprocessing-PCA-Analysis/blob/main/Project%201/data_preprocessing_pca_project.ipynb)

---

## Supervisor
Dr. Mahmoud Gamal

## Authors
- [Basmala ElKady](https://github.com/Basmala-ElKady)
- [Menna Hossny](https://github.com/Mennatullah122)
- [Hoda Mahmoud](https://github.com/HodaMahmoud-2005)
- [Jana Hegazy](https://github.com/janahegazy)
- [Hany Ziad](https://github.com/hanyzead123)
