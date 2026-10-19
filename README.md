# Titanic Survival Prediction 🚢

## 📌 Project Overview
This project aims to predict whether passengers survived the Titanic shipwreck using Machine Learning algorithms. I explored the dataset, performed feature engineering, and implemented classification models to achieve high predictive accuracy.

## 🛠️ Technologies & Libraries
- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:** 
  - `Pandas` & `NumPy` (Data Manipulation)
  - `Matplotlib` & `Seaborn` (Data Visualization)
  - `Scikit-learn` (Machine Learning)
  - `StandardScaler` (Data Preprocessing)

## 📊 Models Implemented
I implemented and compared two powerful classification algorithms:

1. **Random Forest Classifier** 🌲
   - Achieved an accuracy of approximately **83.80%**.
   - Excellent at capturing non-linear relationships in the data.

2. **K-Nearest Neighbors (KNN)** 👥
   - Achieved an accuracy of approximately **82.68%**.
   - Used `StandardScaler` to ensure distance-based calculations were accurate.

## 📈 Key Findings
- **Feature Importance:** The model identified key factors such as `Sex`, `Pclass`, and `Age` as crucial predictors for survival.
- **Data Preprocessing:** Feature scaling was essential for the KNN model to perform effectively.

## 🚀 How to Run
1. Clone this repository.
2. Open `Titanic.ipynb` in Jupyter Notebook or Google Colab.
3. Run all cells to see the complete analysis, visualizations, and model results.

---
*Developed as part of my Data Science learning journey.* 🚀
