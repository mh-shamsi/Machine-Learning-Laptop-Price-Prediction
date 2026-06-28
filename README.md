<div align="center">

# 💻 Machine Learning Laptop Price Prediction

### Predict Laptop Prices Using Multiple Linear Regression

A complete Machine Learning project covering **Data Cleaning**, **Exploratory Data Analysis**, **Feature Engineering**, **Preprocessing**, and **Regression Modeling** with Scikit-Learn.

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikit-learn)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---

# 📖 About The Project

Laptop prices depend on many hardware specifications such as CPU, RAM, GPU, storage type, screen resolution, and manufacturer.

The goal of this project is to build a Machine Learning model capable of estimating laptop prices using these specifications.

This project demonstrates a complete Machine Learning workflow, from raw data preprocessing to model evaluation using **Multiple Linear Regression**.

---

# 📂 Dataset

The dataset contains **1300+ laptops** with various hardware specifications.

## Features

| Feature | Description |
|----------|-------------|
| Company | Laptop manufacturer |
| TypeName | Laptop category |
| Inches | Screen size |
| ScreenResolution | Display resolution |
| Cpu | Processor information |
| Ram | Installed RAM |
| Memory | Storage configuration |
| Gpu | Graphics card |
| OpSys | Operating System |
| Weight | Laptop weight |
| Price_euros | Target variable |

---

# ⚙️ Machine Learning Pipeline

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Encoding
      │
      ▼
Feature Scaling
      │
      ▼
Train/Test Split
      │
      ▼
Multiple Linear Regression
      │
      ▼
Model Evaluation
```

---

# 🔍 Exploratory Data Analysis

Several visualizations were created to better understand the dataset.

### Analysis Included

- Price Distribution
- Company Comparison
- Laptop Type Analysis
- Correlation Analysis
- Numerical Feature Distribution
- Hardware vs Price Relationships

---

# 🧹 Data Cleaning

The preprocessing stage includes:

- Removing unnecessary columns
- Handling inconsistent values
- Converting numerical columns
- Cleaning categorical values
- Preparing features for modeling

---

# 🏗 Feature Engineering

The original dataset contains several complex text columns.

These were transformed into meaningful numerical and categorical features.

---

## 🖥 Screen Resolution

Extracted:

- Horizontal Resolution
- Vertical Resolution
- Pixels Per Inch (PPI)

---

## ⚡ CPU

Extracted:

- CPU Brand
- CPU Model
- CPU Frequency (GHz)

---

## 🎮 GPU

Extracted:

- GPU Brand

---

## 💾 Memory

The storage column was separated into:

- SSD (GB)
- HDD (GB)
- Flash Storage (GB)
- Hybrid Storage (GB)

---

# ⚙️ Data Preprocessing

## Numerical Features

StandardScaler was applied to numerical features including:

- Inches
- RAM
- Weight
- Resolution
- CPU Frequency
- PPI
- Storage Capacities

---

## Categorical Features

One-Hot Encoding was applied to:

- Company
- Laptop Type
- Operating System
- CPU Brand
- CPU Model
- GPU Brand

---

## ColumnTransformer

A **ColumnTransformer** combines both preprocessing pipelines into a single workflow.

---

# 🤖 Model

The project uses

## Multiple Linear Regression

Advantages:

- Fast
- Simple
- Highly Interpretable
- Strong Baseline Model

---

# 📊 Model Performance

| Metric | Value |
|---------|-------|
| MAE | **246.38** |
| RMSE | **356.00** |
| MSE | **126739.53** |
| R² Score | **0.76** |

---

# 📈 Result

The model successfully explains approximately **76%** of the variance in laptop prices.

Considering the simplicity of Linear Regression, this represents a strong baseline for laptop price prediction.

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# 📁 Project Structure

```
Machine-Learning-Laptop-Price-Prediction
│
├── notebook.ipynb
├── laptop_price.csv
├── README.md
└── images
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/mh-shamsi/Machine-Learning-Laptop-Price-Prediction.git
```

Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run Jupyter Notebook

```bash
jupyter notebook
```

Open

```
notebook.ipynb
```

---

# 🎯 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Extraction
- One-Hot Encoding
- StandardScaler
- ColumnTransformer
- Multiple Linear Regression
- Model Evaluation
- Regression Metrics

---

# 🔮 Future Improvements

Future versions of this project could include:

- Ridge Regression
- Lasso Regression
- ElasticNet
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting
- XGBoost
- LightGBM
- Hyperparameter Tuning
- Cross Validation
- Model Deployment with Flask or FastAPI

---

# ⭐ Support

If you found this project useful, consider giving it a **Star ⭐**.

It helps others discover the project and motivates further improvements.

---

<div align="center">

Made with ❤️ using Python & Scikit-Learn

</div>