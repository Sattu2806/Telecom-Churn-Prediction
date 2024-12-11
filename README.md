# Telecom Churn Prediction

## Project Overview

This project focuses on predicting customer churn in the telecom industry, specifically targeting high-value customers who contribute significantly to revenue. By analyzing customer-level data over four months, the objective is to identify potential churners and the key indicators influencing churn behavior.

---

## Business Objective

1. **Predict high-risk customers**: Build predictive models to identify customers likely to churn in the near future.
2. **Identify key churn indicators**: Pinpoint the factors that contribute most to customer churn.

Given the high churn rates (15-25%) and the significant cost of acquiring new customers (5-10 times more than retaining existing ones), this project emphasizes customer retention strategies.

---

## Methods Used

1. **Data Preparation:**
   - Derived new features to enhance prediction.
   - Filtered high-value customers based on recharge behavior.
   - Tagged churners and excluded data from the churn phase.

2. **Exploratory Data Analysis (EDA):**
   - Visualized trends and patterns using Matplotlib and Seaborn.
   - Analyzed customer behavior in "good," "action," and "churn" phases.

3. **Feature Engineering:**
   - Identified relevant predictors of churn.
   - Applied dimensionality reduction techniques like PCA.

4. **Modeling:**
   - Trained multiple classification models, including logistic regression and tree-based models.
   - Addressed class imbalance using oversampling and undersampling techniques.

5. **Evaluation Metrics:**
   - Focused on metrics like Precision, Recall, F1 Score, and ROC-AUC to balance accuracy and churn prediction effectiveness.

---

## Key Learnings

- **Data Imbalance:** Gained insights into handling imbalanced datasets for better prediction accuracy.
- **Behavioral Analysis:** Understood customer lifecycle phases and their influence on churn behavior.
- **Model Insights:** Learned the strengths and trade-offs of various predictive models and feature selection techniques.
- **Business Implications:** Recognized the impact of churn prediction on revenue retention.

---

## Outputs

1. **Churn Prediction Model:**
   - Developed a robust model to identify high-risk customers.
   - Improved prediction accuracy for high-value customers.

2. **Key Indicators of Churn:**
   - Identified top features influencing churn, providing actionable insights for business strategies.

3. **Visualizations:**
   - Illustrated customer behavior, feature importance, and model performance using detailed plots and charts.

---

## Technologies and Tools

- **Programming Language:** Python
- **Libraries:**
  - Pandas and NumPy for data manipulation
  - Matplotlib and Seaborn for visualization
  - Scikit-learn for machine learning models
  - PCA for dimensionality reduction

---

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Sattu2806/Telecom-Churn-Prediction
   ```

2. Run the notebook:
   ```bash
   jupyter notebook Telecom_Churn_Prediction.ipynb
   ```

---

## Conclusion

This project demonstrates the application of machine learning techniques to address customer churn in the telecom industry. By predicting churn and identifying critical indicators, the project provides valuable insights to support customer retention strategies.

