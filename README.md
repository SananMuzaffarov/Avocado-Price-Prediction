# Avocado Price Prediction Project

This project focuses on analyzing and predicting avocado prices in the United States using historical sales data. We applied data science and machine learning techniques to identify trends, patterns, and future prices.

## 📊 Dataset

- **Source**: [Hass Avocado Board via Kaggle](https://www.kaggle.com/datasets/neuromusic/avocado-prices)
- **File**: `Avocado.csv`
- **Features Include**:
  - `Date`: The date of the observation
  - `AveragePrice`: Average price per avocado
  - `Total Volume`: Total number of avocados sold
  - `4046`, `4225`, `4770`: PLU (Product Lookup) codes representing different avocado types
  - `Total Bags`, `Small Bags`, `Large Bags`, `XLarge Bags`
  - `type`: Conventional or organic
  - `year`: Year of observation
  - `region`: Geographic market region in the U.S.

## 📈 Objectives

- Explore and clean avocado price data.
- Perform exploratory data analysis (EDA).
- Build regression models to predict avocado prices.
- Visualize results and insights.
- Evaluate and compare model performance.

## 🧪 Methods & Tools

- **Environment**: Jupyter Notebook
- **Libraries Used**:
  - Pandas & NumPy (data manipulation)
  - Matplotlib & Seaborn (visualization)
  - Scikit-learn (machine learning)
  - Statsmodels (statistical analysis)

## 🔍 Key Highlights

- Detailed EDA including region-wise trends and yearly price changes.
- Applied multiple regression techniques including:
  - Linear Regression
  - Random Forest Regressor
  - Decision Tree
- Included data preprocessing steps like encoding, feature scaling, and train-test split.
- Visualized prediction results to evaluate model accuracy.

## 📁 Files

- `AvocadoGroupProject.ipynb`: Main notebook containing code, analysis, and model building.
- `Avocado.csv`: Dataset used for training and evaluation.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/avocado-price-prediction.git
   cd avocado-price-prediction
   
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   
3. Launch the notebook:
   ```bash
   jupyter notebook AvocadoGroupProject.ipynb
