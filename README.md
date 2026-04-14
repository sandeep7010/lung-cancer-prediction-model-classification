# Lung Cancer Prediction Model Classification

## 📌 Project Overview

This project predicts the likelihood of lung cancer using machine learning algorithms.
The model analyzes health-related factors from a dataset and classifies whether a person is at risk of lung cancer.

The project is implemented using Python in a Jupyter Notebook and uses machine learning libraries for data analysis, visualization, and prediction.

---

### 🚀 Project Workflow

1. **Data Collection**
   The dataset containing patient diagnostic and lifestyle information was loaded for analysis.

2. **Data Preprocessing**

   * Handled missing values using imputation techniques.
   * Detected and treated outliers using the **IQR method**.
   * Encoded categorical variables using **Label Encoding / One-Hot Encoding**.
   * Balanced the dataset using **SMOTE or undersampling**.

3. **Exploratory Data Analysis (EDA)**

   * Performed statistical analysis to understand data distribution.
   * Created visualizations such as histograms, boxplots, and correlation heatmaps.
   * Analyzed relationships between features and the target variable.

4. **Model Training**
   Trained multiple machine learning models including:

   * Logistic Regression
   * Random Forest
   * Gradient Boosting
   * Support Vector Machine (SVM)
   * XGBoost

5. **Model Evaluation**
   Evaluated model performance using:

   * Accuracy
   * Precision
   * Recall
   * F1 Score
   * ROC-AUC

6. **Model Comparison and Selection**
   Compared the performance of different models and selected the best-performing model.

7. **Model Saving**
   Saved the final trained model pipeline for future predictions.

---

### 💡 Key Insights

* The dataset required **extensive preprocessing** due to missing values and class imbalance.
* **Exploratory Data Analysis** helped identify patterns and correlations among features.
* **Tree-based algorithms** such as Random Forest and Gradient Boosting provided better prediction performance compared to simpler models.
* Proper **feature encoding and outlier handling** significantly improved model accuracy.
* The developed pipeline ensures **reproducibility and scalability** for healthcare prediction tasks.

---
## Files

| File                        | Description                                                              |
| --------------------------- | ------------------------------------------------------------------------ |
| `lung_dataset.csv`          | Patient diagnosis dataset used for lung cancer prediction                |
| `lung_cancer_project.ipynb` | Main notebook containing EDA, preprocessing, model training & evaluation |
| `best_model_pipeline.pkl`   | Saved best machine learning model pipeline                               |
| `model_comparison.csv`      | Comparison of different model performance metrics                        |
| `README.md`                 | Project overview, workflow, and insights                                 |


### 🧠 Tech Stack

* **Programming Language:** Python
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn
* **Advanced ML Model:** XGBoost
* **Development Environment:** Jupyter Notebook
* **Version Control:** Git and GitHub
