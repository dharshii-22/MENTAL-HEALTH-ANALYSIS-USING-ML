## 🧠 Mental Health Prediction Using Machine Learning

This project presents a predictive machine learning framework to assess the likelihood of individuals requiring mental health treatment, using workplace survey data. The system leverages multiple supervised learning models, ensemble methods, and SHAP interpretability to build an explainable and scalable mental health analytics tool.

---

## 📌 Project Highlights

- Predicts need for **mental health treatment** based on workplace-related and demographic data
- Implements advanced models: **XGBoost, LightGBM, CatBoost, Random Forest, Gradient Boosting**
- Handles **class imbalance** using **SMOTETomek**
- Explains predictions using **SHAP (SHapley Additive exPlanations)**
- Deployable via **web interface** for real-time predictions

---

## 🔍 Dataset

- Source: [Open Mental Health in Tech Survey](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-survey)
- Features:
  - Age
  - Gender
  - Family History
  - Work Interference
  - Self-employment
  - Mental Health Treatment (target)

---

## 🛠️ Technologies Used

- Python 3.x
- Scikit-learn
- XGBoost, LightGBM, CatBoost
- Pandas, NumPy
- Matplotlib, Seaborn
- SHAP
- Streamlit / Flask (for deployment)


###  Model Evalution

| Model          | Accuracy | ROC-AUC | Log Loss |
| -------------- | -------- | ------- | -------- |
| XGBoost        | 99.6%    | 0.99    | 0.22     |
| LightGBM       | 98.7%    | 0.98    | 0.24     |
| CatBoost       | 98.2%    | 0.97    | 0.26     |
| Random Forest  | 97.9%    | 0.95    | 0.30     |
| Gradient Boost | 97.3%    | 0.94    | 0.31     |

### Sample Output 
![image](https://github.com/user-attachments/assets/f2c3b43b-deba-4000-a08a-b6de02eaf39e)

📬 Contact
Mail ID - dharshiny2005@gmail.com
GitHub: https://github.com/dharshii-22
