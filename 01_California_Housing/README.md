# California Housing Price Prediction

This project focuses on predicting housing prices in California using machine learning regression techniques. It includes comprehensive Exploratory Data Analysis (EDA) and model performance comparisons.

## 📌 Project Overview
The goal of this project is to analyze the factors affecting housing prices in California and build a predictive model. The workflow includes:
- **Exploratory Data Analysis (EDA):** Statistical summaries, outlier detection using boxplots, and feature correlation analysis.
- **Modeling:** Implementing and comparing Linear Regression and Random Forest Regressor models.
- **Evaluation:** Assessing models based on Mean Squared Error (MSE) and R2 Score.

## 📂 Repository Structure
- `notebooks/`: Contains the Jupyter Notebook (`California_Housing_Dataset.ipynb`) with all analysis and code.
- `data/`: Directory for raw and processed datasets.
- `results/`: Stores exported visualizations, saved models, and performance metrics.

## 📊 Dataset
The project uses the **California Housing dataset** fetched from `sklearn.datasets`.
- **Features:** Median Income, House Age, Average Rooms, Average Bedrooms, Population, Average Occupancy, Latitude, and Longitude.
- **Target Variable:** Price (Median House Value).

## 🛠️ Requirements
To run this project, you need the following Python libraries installed:
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `scikit-learn`

You can install them via pip:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn
