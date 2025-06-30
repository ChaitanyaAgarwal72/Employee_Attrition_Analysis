# 📊 Employee Attrition Analysis

This project performs an end-to-end analysis and prediction of employee attrition using machine learning. The goal is to help organizations identify key drivers of employee turnover and proactively retain talent.

---

## 📁 Dataset

- Source: [IBM HR Analytics Attrition Dataset on Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- Contains information about 1,470 employees with 35 features such as job role, department, age, salary, work-life balance, etc.

---

## 🧰 Tools and Libraries Used

- Python (Pandas, NumPy)
- Data Visualization: Seaborn, Matplotlib
- Scikit-learn (Label Encoding, Model Training, Evaluation)
- Google Colab for development

---

## 📌 Project Workflow

1. **Data Cleaning**  
   - Removed redundant columns  
   - Handled categorical features using Label Encoding

2. **Exploratory Data Analysis (EDA)**  
   - Visualized attrition across departments, job roles, and overtime  
   - Used boxplots to analyze feature distributions and outliers

3. **Feature Engineering & Preprocessing**  
   - Converted data for modeling  
   - Scaled numerical features

4. **Model Training and Evaluation**  
   - Trained and compared 3 models:
     - Logistic Regression
     - Random Forest Classifier
     - Gradient Boosting Classifier  
   - Evaluated using F1-score, Precision, Recall

5. **Key Insights**
   - Overtime, Monthly Income, Job Role, and Distance From Home were strong indicators of attrition  
   - Employees working overtime or living farther from the office had higher attrition rates.

---

## 📈 - Model Comparison:
  - Three models were built and evaluated:  
    - Logistic Regression
    - Random Forest Classifier 
    - Artificial Neural Networks

---

## 📌 Conclusion

This analysis helps HR departments understand which employee characteristics are most predictive of attrition. It supports better talent retention strategies using data-driven insights.

---

## 📎 How to Run

1. Download or clone the repository.
2. Open the notebook in [Google Colab](https://colab.research.google.com/) or Jupyter.
3. Make sure to download the dataset from [this Kaggle link](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset) and upload it to your runtime.
4. Run all cells step-by-step to replicate the analysis and results.

---

## 🙏 Thank You!
