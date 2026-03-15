# Weather Temperature Analysis: EDA & Feature Engineering

This project focuses on the preprocessing and exploratory analysis of a weather dataset to prepare it for predictive modeling.

## 🛠️ Key Data Science Tasks
* **Missing Value Management:** Applied two distinct methods (e.g., Mean Imputation and Row Deletion) to ensure dataset integrity.
* **Feature Normalization:** Performed Min-Max scaling (0-1) to ensure feature parity and accelerate gradient descent convergence.
* **Categorical Encoding:** Identified and transformed non-numeric variables into machine-readable formats.
* **Feature Engineering:** Derived a new target variable, `Next_Taverage`, by calculating the mean of daily maximum and minimum temperatures.
* **Correlation Analysis:** Leveraged Heatmaps and Scatterplots to identify and remove redundant, highly-correlated variables to prevent multicollinearity.

## 📊 Visualizations Included
* **Correlation Heatmap:** To visualize relationships between 20+ weather variables.
* **Scatterplots:** Exploring the linear relationship between features and the target temperature.
