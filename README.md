# 🏡 ML_HandsON – California Housing Price Prediction

This repository contains a hands-on machine learning project focused on predicting housing prices in California using census data. Inspired by Chapter 2 of *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow*, this project walks through the full machine learning pipeline from raw data to model evaluation.

---

## 📊 Project Overview

We aim to build a machine learning model to predict median house values in California districts based on features such as location, number of rooms, and population density.

The dataset includes features like:

- **Geographic data** (`longitude`, `latitude`)
- **Demographics** (`population`, `households`, `median_income`)
- **Housing stats** (`total_rooms`, `total_bedrooms`, `housing_median_age`)
- **Categorical data** (`ocean_proximity`)

---

## ✅ Project Milestones

### ✔️ Data Exploration & Preprocessing

- ✅ Loaded California housing data from CSV
- ✅ Inspected missing values (`total_bedrooms`)
- ✅ Visualized distributions & relationships via histograms and scatter plots
- ✅ Created income categories for stratified sampling
- ✅ Performed stratified train/test split

### ✔️ Feature Engineering & Transformation

- ✅ Engineered new features (e.g., `rooms_per_household`)
- ✅ Handled missing values using median imputation
- ✅ Encoded categorical features (`ocean_proximity`)
- ✅ Applied feature scaling and standardization

### ✔️ Modeling & Evaluation (To be done)

- ☐ Set up a transformation pipeline
- ☐ Select and train regression models (e.g., Linear Regression, Decision Tree, Random Forest)
- ☐ Fine-tune using cross-validation/grid search
- ☐ Evaluate performance on test data

---

## 🧪 Data Snapshot

| Longitude | Latitude | Median Age | Total Rooms | Total Bedrooms | Population | Households | Income | Median Value | Proximity |
|-----------|----------|------------|-------------|----------------|------------|------------|--------|---------------|-----------|
| -122.23   | 37.88    | 41         | 880         | 129            | 322        | 126        | 8.3252 | 452600        | NEAR BAY  |
| -122.22   | 37.86    | 21         | 7099        | 1106           | 2401       | 1138       | 8.3014 | 358500        | NEAR BAY  |

---

## 📉 Visualizations

- Income category distribution
- Attribute histograms and correlation matrix
- Geographical scatter plot of house values


---

## 🛠️ Tech Stack

- Python 3.9+
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/ML_HandsON.git
cd ML_HandsON

# (Optional) Set up a virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Run the notebook or script
jupyter notebook housing_analysis.ipynb
```
