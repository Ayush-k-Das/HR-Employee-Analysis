# HR Employee Analysis 📊

This repository contains a complete analysis of HR Employee data, including:
- **Dataset exploration**
- **Excel-based dashboard reporting**
- **Machine Learning model for attrition prediction**

---

## 📂 Contents
1. **Dataset**
   - `data/HR_Employee_Data.csv`  
   Contains employee records including demographics, job details, and attrition information.

2. **Excel Dashboard**
   - `excel_dashboard/HR_Employee_Analytics.xlsx`  
   Interactive Excel dashboard analyzing:
   - Attrition by Age, Gender, Department, Education, Job Role, Marital Status
   - Overall attrition rate & employee distribution
   - Key HR insights like average age and job satisfaction rating


3. **Attrition Prediction Model**
   - `model/HR_Attrition_Prediction.ipynb`  
   Jupyter Notebook performing:
   - Data Cleaning & Preprocessing
   - Exploratory Data Analysis (EDA)
   - Encoding categorical features
   - Standard Scaling for numeric features
   - Logistic Regression / RandomForest model training
   - Model evaluation with Accuracy, F1, Precision, Recall

---

## 🚀 Getting Started

### 1. Clone Repository
```bash
git clone https://github.com/<your-username>/Hr-Employee-Analysis.git
cd Hr-Employee-Analysis
2. Run Jupyter Notebook
jupyter notebook model/HR_Attrition_Prediction.ipynb

📊 Dashboard Highlights
Total Employees: 1470

Attrition: 237 employees (16.12%)

Male-Female ratio: 60%-40%

Highest attrition in Sales & R&D

Most affected group: Employees aged 25–34

Job Satisfaction Rating: 2.6 (out of 5)

⚡ Results
The ML model predicts whether an employee is likely to leave the company with:

Accuracy: ~84–88% (depends on train/test split)

Balanced evaluation using F1 Score and Precision/Recall

🛠️ Tech Stack
Python (pandas, numpy, seaborn, matplotlib, scikit-learn)

Excel (pivot tables, slicers, dashboards)

Jupyter Notebook

📌 Use Cases
Identify high-risk attrition groups

Support HR decision-making

Enhance employee retention strategies

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
