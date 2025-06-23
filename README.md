#  Electric Vehicle Population 2024-25 Data Analysis 

This project presents a complete data analysis Electric Vehicle Population 2024-25 dataset. The goal is to uncover insights about EV adoption trends and build a machine learning model to predict the type of electric vehicles based on vehicle and location features.

![Image](https://github.com/user-attachments/assets/ad49c50b-9f03-446a-aacd-821479749551)

## 📁 Dataset Overview

- **Source**: [Kaggle - Electric Vehicle Population Data](https://www.kaggle.com/datasets/utkarshx27/electric-vehicle-population-data/data)
- **Filename**: `Electric_Vehicle_Population_Data.csv`  
- **Features Include**:
  - Model Year, Make, Model, Vehicle Type
  - Electric Range, Electric Utility
  - City, State, ZIP Code, and more


## 📊 Project Highlights

### 🔍 Data Cleaning
- Dropped irrelevant and sparse columns like `VIN` and `DOL Vehicle ID`
- Handled missing values in key columns with imputation and removal
- Converted categorical data into numeric using Label Encoding

### 📈 Exploratory Data Analysis (10 Graphs)
- Top 10 EV manufacturers and cities
- Distribution of vehicle age and model years
- Pie chart of EV type share
- Heatmap of feature correlations
- Boxplot and scatterplot visualizations

### ⚙️ Feature Engineering
- Created `Vehicle_Age` feature from model year
- Encoded key categorical features for ML

### 🤖 Machine Learning Model
- **Model Used**: Random Forest Classifier  
- **Target**: Predict `Electric Vehicle Type`  
- **Evaluation Metrics**: Accuracy Score, Classification Report, Confusion Matrix

## 🧠 Key Insights

- Majority of electric vehicles are concentrated in top cities like Seattle and Bellevue
- Battery Electric Vehicles (BEVs) dominate over Plug-in Hybrid types
- Most vehicles are between 0–5 years old, indicating recent adoption
- Strong brand dominance observed among top manufacturers (Tesla, Nissan, etc.)
