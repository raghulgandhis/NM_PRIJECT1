# 📉 Customer Churn Prediction using Machine Learning

## 🔍 Overview

Customer churn is one of the most critical problems faced by businesses, especially in subscription-based services like telecom, SaaS, and banking. Predicting customer churn helps companies retain customers by identifying who is at risk of leaving and proactively addressing their concerns.

In this project, we leverage machine learning techniques to build a predictive model that identifies customers likely to churn based on historical data. The model can be used by business teams to design targeted interventions to reduce churn.

---

## 🧠 Objectives

* To explore and understand customer behavior through data analysis.
* To build and evaluate machine learning models for predicting customer churn.
* To interpret the model’s predictions using explainability tools.
* To develop actionable business strategies based on predictions.

---

## 📂 Project Structure

```
customer-churn-ml/
│
├── data/                    # Raw and processed datasets
├── notebooks/               # Jupyter notebooks for EDA, model training, etc.
├── src/                     # Python source code files
├── models/                  # Saved machine learning models
├── reports/                 # Project report and visualizations
├── requirements.txt         # Project dependencies
└── README.md                # Project overview
```

---

## 🛠️ Technologies Used

* Python (Pandas, NumPy, Scikit-learn, XGBoost)
* Jupyter Notebook
* Matplotlib / Seaborn
* Streamlit (for optional dashboard)
* SHAP / LIME (for model interpretability)

---

## 📊 Machine Learning Models Used

* Logistic Regression
* Decision Trees
* Random Forest
* XGBoost
* Support Vector Machines (SVM)

Model performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC Score

---

## 👥 Team Members and Roles

| Member Name  | Role                                     | Responsibilities                                                                                            |
| ------------ | ---------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| **S.RAGHUL GANDHI** | Project Manager / Business Analyst       | Defined the problem statement, coordinated team tasks, aligned business goals with technical outcomes.      |
| **P.MOHAMMED IRSHAD AHAMED** | Data Engineer                            | Handled data collection, cleaning, preprocessing, and feature engineering.                                  |
| **P.IDHAYA** | Machine Learning Engineer                | Built and tuned machine learning models, performed cross-validation and optimization.                       |
| **AARIF SUHAIL** | Data Analyst                             | Performed exploratory data analysis, generated visualizations and insights, assisted in feature selection.  |
| **A.ALTHAF BASHA** | Model Evaluation & Deployment Specialist | Evaluated model performance, applied explainability tools (SHAP/LIME), and contributed to deployment setup. |

---

## 📈 Results and Insights

* Our best model achieved an **F1-score of XX%** and **ROC-AUC of YY%**.
* Key churn indicators included: **Tenure**, **Monthly Charges**, **Contract Type**, and **Customer Service Calls**.
* SHAP analysis revealed that customers with short tenure and high monthly charges are more likely to churn.

---

## 🚀 Future Work

* Integrate real-time data for live predictions.
* Deploy model using Flask or Streamlit.
* Explore deep learning models for better accuracy.
* Improve model interpretability using advanced techniques.

---

## 📝 How to Run

1. Clone the repo:

   ```bash
   git clone :https://github.com/raghulgandhis/NM_PRIJECT1
   cd customer-churn-ml
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run notebooks or Python scripts in `src/` to train and evaluate models.

---

## 📬 Contact

For any inquiries or collaborations, feel free to contact any team member or raise an issue in the repository.

---raghul31102005@gmail.com

Would you like a project report or presentation template based on this content?
