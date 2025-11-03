Heart Disease Data Mining Project

## Overview
This deliverable is part of Advanced Data Mining for Data-Driven insights and Predictive Modeling, further designed to guide through key stages of the data mining process - from data collection and cleaning to model building and pattern discovery.  
This repository contains **Deliverable 1: Data Collection, Cleaning, and Exploration**.

---

## Dataset Summary
**Dataset:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)  
**Records:** 303  
**Attributes:** 14 (mix of numerical and categorical)  
**Target:** Presence of heart disease (`1 = yes`, `0 = no`)

**Selected because:**
- Contains both numeric and categorical variables
- Suitable for classification, regression, and clustering
- Real-world healthcare application

---

## Data Cleaning Steps
1. **Loaded dataset** and verified structure using Pandas.  
2. **Checked for missing values** — none found.  
3. **Removed duplicates** to ensure data quality.  
4. **Validated categorical values** for consistency.  
5. **Detected outliers** using boxplots and IQR visualization.  
6. **Converted categorical variables** to `category` dtype for better handling.

---

## Exploratory Data Analysis
- Visualized **feature distributions** (histograms, boxplots)
- Explored **relationships** using correlation heatmap and pairplots
- Found that **chest pain type, max heart rate, and exercise-induced angina** are key predictors of heart disease

**Key Visuals:**
- Correlation Heatmap  
- Pairplot by Target  
- Distribution Histograms for numerical features  

---

## Tools Used
- Python 3.9+
- Pandas
- Seaborn
- Matplotlib
- NumPy
- Jupyter Notebook

---

## Challenges & Resolutions
| Challenge | Resolution |
|------------|-------------|
| Noisy or inconsistent categorical values | Normalized encodings and converted to categorical data type |
| Detecting outliers | Used boxplots and IQR method for visualization |
| Understanding relationships between features | Used correlation heatmaps and pairplots for visual exploration |

---
