# Diamond Price Prediction: Linear vs. Polynomial Regression

This project analyzes the physical and quality attributes of diamonds to predict their prices. It explores data cleaning, feature encoding, and compares basic Linear Regression with higher-degree Polynomial models.

## 📂 Project Structure
- `data/`: Contains the raw diamonds dataset.
- `notebooks/`: Detailed Jupyter Notebook with EDA, outlier cleaning, and modeling steps.
- `results/`: Performance metrics and visualizations (Residual plots, Actual vs Predicted graphs).

## 📊 Dataset Overview
The dataset includes 53,940 diamonds with 10 features:
- **Physical:** Carat, x, y, z, depth, table.
- **Quality (Categorical):** Cut, Color, Clarity.
- **Target:** Price in USD.

## 🛠️ Key Steps Taken
1. **Data Cleaning:** Removed invalid entries where dimensions (x, y, z) were zero and filtered extreme outliers.
2. **Feature Engineering:** Implemented **Ordinal Encoding** on categorical features (Cut, Color, Clarity) to preserve their natural ranking.
3. **Modeling:** - Built a **Linear Regression** baseline.
   - Developed **Polynomial Regression** models to capture non-linear relationships.
4. **Evaluation:** Used R2 Score, MAE, and RMSE to compare performance and analyzed the Bias-Variance trade-off to find the optimal polynomial degree.

## 📈 Performance Summary
| Model | R2 Score | MAE |
| :--- | :--- | :--- |
| Linear Regression | 0.88 | $800 |
| **Polynomial (Deg 2)** | **0.96** | **$400** |

The Polynomial model shows a significant improvement, proving that diamond prices do not scale linearly with their attributes.

## 🚀 How to Run
1. Clone the repository.
2. Install requirements: `pip install pandas seaborn scikit-learn matplotlib`.
3. Open `notebooks/Diamond_Dataset.ipynb` to see the full analysis.
