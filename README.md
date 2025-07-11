# 🚀 NEO Hazard Detection using Machine Learning

This project focuses on detecting whether a Near-Earth Object (NEO) is **hazardous** or **non-hazardous** using machine learning classification algorithms. It leverages historical NEO data from NASA and applies ML techniques to build a robust prediction model.

---

## 📌 Problem Statement

Near-Earth Objects (NEOs) are asteroids or comets that come close to Earth's orbit. Some of these objects may pose a potential threat to Earth. The objective of this project is to develop a machine learning model that can classify whether a given NEO is **potentially hazardous** or **not**, based on various features such as diameter, speed, distance, etc.

---

## 🧠 Technologies Used

- Python 🐍
- Pandas & NumPy for data manipulation
- Matplotlib & Seaborn for visualization
- Scikit-learn for machine learning
- Jupyter Notebook / Google Colab for development

---

## 📂 Dataset

- **Source**: [NASA NEO API / Kaggle Dataset](https://data.nasa.gov/)
- **Features Used**:
  - `est_diameter_min`
  - `est_diameter_max`
  - `relative_velocity`
  - `miss_distance`
  - `absolute_magnitude`
  - `is_hazardous` (target variable)

---

## 🧪 Model Building

- **Data Preprocessing**:
  - Missing value handling
  - Feature selection
  - Scaling / Normalization
  - Encoding (if required)

- **Models Used**:
  - Logistic Regression
  - Random Forest Classifier
  - XGBoost Classifier
  - Support Vector Machine

- **Evaluation Metrics**:
  - Accuracy
  - Precision, Recall
  - F1-Score
  - Confusion Matrix

---

## ✅ Results

| Model               | Accuracy | F1-Score | Remarks                       |
|--------------------|----------|----------|-------------------------------|
| Logistic Regression| 92%      | 0.89     | Baseline model                |
| Random Forest      | 95%      | 0.93     | Best performing model         |
| XGBoost            | 94%      | 0.92     | Slightly better than baseline |
| SVM                | 91%      | 0.88     | Good but slower training      |

---

## 📈 Visualizations

- Feature correlation heatmap
- Distribution of hazardous vs non-hazardous
- Feature importance plot
- ROC Curve for classifiers

---
