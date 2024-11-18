# Wine Quality Analysis

## Overview  
This project involves exploratory data analysis (EDA) on a wine quality dataset to understand the relationships between various chemical properties and wine quality. Visualizations and statistical insights were used to analyze trends and distributions of data.  

---

## Project Objectives  
- Preprocess and clean the dataset by handling duplicate values and ensuring data integrity.  
- Explore relationships between features and wine quality using correlation analysis.  
- Visualize data distributions and trends using univariate, bivariate, and multivariate analyses.  
- Identify imbalances in the target variable (wine quality) and analyze key influencing factors like alcohol and pH.  

---

## Dataset  
- **Source**: [Wine Quality Dataset]((https://github.com/KVenkataPavani/EDA-Python-Project-Red-Wine-Quality/blob/main/winequality-red.csv))  
- **Features**: Various physicochemical properties of wine, including alcohol, pH, acidity, and residual sugar.  
- **Target Variable**: Wine quality (integer scores).  

---

## Workflow  

### 1. Data Preprocessing  
- Loaded the dataset and checked its structure using `info()` and `describe()`.  
- Identified and removed duplicate records to improve data quality.  

### 2. Exploratory Data Analysis (EDA)  
- Checked for missing values and unique values in the target column (`quality`).  
- Performed statistical correlation analysis and visualized the heatmap to identify relationships between features.  
- Analyzed data imbalance in wine quality using bar plots.  

### 3. Visualizations  
- **Univariate Analysis**: Plotted histograms and KDE plots for all features to observe distributions.  
- **Bivariate Analysis**: Studied relationships between pairs of features using scatter plots and box plots.  
- **Multivariate Analysis**: Explored relationships between multiple variables with pair plots.  

### 4. Key Insights  
- Alcohol positively correlates with wine quality.  
- The dataset is imbalanced, with certain quality scores appearing more frequently.  

---

## Technologies Used  
- **Programming Language**: Python  
- **Libraries**: Pandas, Matplotlib, Seaborn   

