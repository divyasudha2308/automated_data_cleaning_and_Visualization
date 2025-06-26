# 🏡 Ames Housing Data Cleaning & Visualization Project

This project focuses on the **data cleaning**, **exploratory data analysis (EDA)**, and **visualization** of the **Ames Housing dataset**, a comprehensive real-estate dataset with 80+ features describing residential homes in Ames, Iowa. The dataset provides a rich variety of categorical, ordinal, and numerical data, ideal for understanding preprocessing pipelines in real-world machine learning workflows.

---

## 📊 Objective

- ✅ Perform **data cleaning** on missing, inconsistent, or categorical values
- ✅ Explore feature distributions, correlations, and outliers
- ✅ Visualize patterns influencing **housing prices**
- ✅ Prepare the dataset for downstream **modeling** or **prediction tasks**

---

## 🛠️ Skills Demonstrated

### 🔹 **Data Analysis & Cleaning**
- Handling missing values: categorical (`NA`) and numerical (`0`, blanks)
- Imputing data using statistical (mean, mode) and domain-based techniques
- Label encoding and one-hot encoding of categorical variables
- Feature transformation and normalization

### 🔹 **Data Visualization**
- Univariate & bivariate plots (histograms, box plots, bar charts)
- Correlation heatmaps to analyze numerical feature relationships
- Bar plots for quality scores (e.g., `OverallQual`, `ExterQual`)
- Price distribution by categorical features (e.g., `Neighborhood`, `HouseStyle`)

### 🔹 **Feature Understanding & Domain Knowledge**
- Property characteristics: lot shape, frontage, land slope
- Structural features: house style, roof type, exterior material
- Utilities and condition: basement finish, garage quality, fence type
- Transaction context: sale condition, zoning, and month/year sold

---

## 🗂️ Dataset Overview

The dataset includes over **80 features**, grouped into the following categories:

- **Location**: `Neighborhood`, `Condition1`, `LotConfig`
- **Building Structure**: `HouseStyle`, `RoofStyle`, `Exterior1st`, `GarageType`
- **Quality Ratings**: `OverallQual`, `ExterQual`, `KitchenQual`, `BsmtQual`
- **Area Measurements**: `LotArea`, `GrLivArea`, `TotalBsmtSF`, `GarageArea`
- **Amenities**: `Fireplaces`, `PoolQC`, `Fence`, `MiscFeature`
- **Transaction Info**: `YrSold`, `MoSold`, `SaleType`, `SaleCondition`

---

## 📈 Key Insights

- High positive correlation found between `GrLivArea` and `SalePrice`
- Neighborhood plays a significant role in house pricing
- Quality scores like `OverallQual` and `KitchenQual` strongly influence sale price
- Categorical variables like `MSZoning`, `BldgType`, and `GarageFinish` provide key price segmentation

---

## 🧰 Tools & Libraries Used

- **Python**
- **Pandas** – data handling and preprocessing
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – for advanced plotting
- **Scikit-learn** – for preprocessing and future modeling

---

## 📎 Example Visualizations

- Heatmap of feature correlations with `SalePrice`
- Violin plot: `OverallQual` vs. `SalePrice`
- Boxplot: `Neighborhood` vs. `SalePrice`
- Distribution plot of `SalePrice` before and after log transformation

---

## 🔍 Future Scope

- Build a predictive model (e.g., Linear Regression, XGBoost)
- Apply PCA or Feature Selection techniques
- Hyperparameter tuning & cross-validation
- Build a Streamlit web app to deploy EDA results interactively

---

## 🧑‍💻 Author

**Divya Sudha Kolli**  
3rd Year B.Tech CSE (AI & ML)  
CMR College of Engineering & Technology, Hyderabad

---

## 📁 Dataset Source

- [Ames Housing Dataset (Kaggle)](https://www.kaggle.com/datasets/prevek18/ames-housing-dataset)
- Originally curated by **Dean De Cock**, widely used for regression problems in data science

---

