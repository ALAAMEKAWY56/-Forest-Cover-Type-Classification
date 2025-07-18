# 🌲 Forest Cover Type Classification

## 📌 Project Overview
This project focuses on predicting the **type of forest cover** based on **cartographic and environmental features** such as elevation, slope, and soil types using machine learning. We implemented and compared **Random Forest** and **XGBoost** models to achieve high classification performance on the UCI Covertype dataset.

---

## 🚀 Key Highlights
- **Models Used:** Random Forest & XGBoost.
- **Performance Metrics:**
  | Metric       | Random Forest | XGBoost  |
  |--------------|---------------|----------|
  | Accuracy     | 0.9551        | **0.9614** |
  | Precision    | **0.9461**    | 0.9363   |
  | Recall       | 0.9085        | **0.9483** |
  | F1 Score     | 0.9260        | **0.9422** |
  
- **Feature Importance:** Elevation, Wilderness Area, and certain Soil Types were identified as the top predictors.
- **Class Imbalance Handling:** Used `class_weight` for Random Forest and `sample_weight` for XGBoost to improve recall on minority classes.
- **Hyperparameter Tuning:** Optimized `n_estimators`, `max_depth`, and `learning_rate` using GridSearchCV.

---

## 🛠 Tools & Libraries
- Python, Pandas, NumPy
- Scikit-learn (Random Forest, metrics)
- XGBoost
- Matplotlib, Seaborn (visualizations)

---

## 📈 Visualizations
- Confusion matrices for both models.
- Side-by-side feature importance plots for Random Forest vs XGBoost.
- Model comparison table.

---

## 🧩 How to Run
1. Clone the repository:

   git clone https://github.com/ALAAMEKAWY56/forest-cover-classification.git

2. Install dependencies:

  pip install -r requirements.txt

3.Run the notebook:

  jupyter notebook Forest_Cover_Classification.ipynb

---

## 📘 License

This project is licensed for educational and personal use.

---

## 🙋‍♀️ Author

**Alaa Mohamed Mekawi**  
Computer Engineer | Data & AI Enthusiast

---

