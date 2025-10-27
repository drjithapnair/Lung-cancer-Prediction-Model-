

## 🩺 Detecting Lung Cancer Using Patient Diagnosis Data

This project applies **data science and machine learning** techniques to predict patient survival outcomes based on diagnostic and treatment data.
It includes **EDA, preprocessing, outlier handling, feature encoding, model training, and evaluation** using multiple algorithms.

---

### 🚀 Project Workflow

1. **Data Preprocessing**

   * Missing value handling using `SimpleImputer`
   * Outlier capping with the **IQR method**
   * Label/One-Hot Encoding of categorical variables
   * Class balancing using undersampling / SMOTE

2. **Exploratory Data Analysis (EDA)**

   * Statistical summary
   * Visualizations (class balance, boxplots, histograms, correlation heatmap, etc.)

3. **Model Building**

   * Trained multiple models:

     * Logistic Regression
     * Random Forest
     * Gradient Boosting
     * Support Vector Machine
     * XGBoost

4. **Evaluation Metrics**

   * Accuracy, Precision, Recall, F1-score, ROC-AUC
   * ROC curve visualization
   * Model comparison table

5. **Model Saving**

   * Best model saved as `best_model_pipeline.pkl`
   * Model comparison saved as `model_comparison.csv`

---

### 🧠 Tech Stack

* **Python**
* **Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib**
* **XGBoost (optional)**
* **Jupyter Notebook**

---

### 📁 Files

| File                            | Description                                         |
| ------------------------------- | --------------------------------------------------- |
| `dataset_med.csv`               | Patient diagnosis dataset                           |
| `lung_cancer_ml_pipeline.ipynb` | Main notebook with EDA, model building & evaluation |
| `best_model_pipeline.pkl`       | Saved best model pipeline                           |
| `model_comparison.csv`          | Evaluation summary                                  |
| `README.md`                     | Project overview                                    |

---

### 💡 Key Insights

* The dataset required extensive preprocessing and balancing due to class imbalance.
* Tree-based models (Random Forest, Gradient Boosting, XGBoost) performed best.
* The workflow ensures full reproducibility and scalability for healthcare prediction use cases.

---
