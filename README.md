# 🛒 Big Mart Sales Prediction

## 📌 Project Overview
This project aims to predict product sales at Big Mart outlets using Machine Learning regression models.  
The objective is to help retail businesses improve inventory planning and revenue forecasting.

---

## 🎯 Problem Statement
To build a predictive model that estimates `Item_Outlet_Sales` using product and outlet features such as:
- Item Type
- Item MRP
- Item Visibility
- Outlet Size
- Outlet Location Type
- Outlet Type

---

## 📊 Dataset
The dataset consists of:
- `Train.csv` (includes target variable)
- `Test.csv` (used for prediction)

Target Variable:
- **Item_Outlet_Sales**

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Project Workflow
1. Data Cleaning
2. Handling Missing Values
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Building (Linear Regression, Random Forest)
6. Model Evaluation (RMSE, R² Score)

---

## 📈 Model Performance
Random Forest Regressor performed better compared to Linear Regression.


---

## 🚀 How to Run the Project

1) Clone the repository:
</> Bash
git clone https://github.com/kaushiktewari0609-lgtm/Big_mart_sales_prediction.git

2) Install required libraries:
</> Bash
pip install -r requirements.txt

If requirements.txt is not available, install manually:
</> Bash
pip install pandas numpy matplotlib seaborn scikit-learn

Run the Notebook:

Open Jupyter Notebook:
</>Bash
jupyter notebook

Then open:
</> Code
Big_Mart_Sales_Prediction.ipynb


---

## 📌 Project Structure

Big-Mart-Sales-Prediction/
│
├── Train.csv
├── Test.csv
├── Big_Mart_Sales_Prediction.ipynb
├── Project_Report.docx
├── Project_Synopsis.docx
├── README.md
└── requirements.txt


---

## 🎯 Future Improvements

1) Implement XGBoost for better performance
2) Perform hyperparameter tuning
3) Deploy the model using Flask or Streamlit
4) Create a web-based prediction interface


---

## 📜 Conclusion

This project demonstrates how Machine Learning can be used to solve real-world retail problems. Predictive analytics helps businesses optimize operations and make data-driven decisions.
