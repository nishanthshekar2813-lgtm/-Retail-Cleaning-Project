# 🛒 Retail Data Analysis & Machine Learning Project

## 📌 Project Overview

This project focuses on analyzing retail customer data to extract insights and build predictive models. It is divided into three main tasks:

* **Task 1:** Data Cleaning & Visualization
* **Task 2:** Predictive Modeling (Machine Learning)
* **Task 3:** Exploratory Data Analysis (EDA)

---

## 📂 Dataset Description

The dataset contains customer transaction details:

* Customer_ID
* Age
* Gender
* City
* Product_Category
* Price
* Quantity
* Purchase_Date
* Payment_Method
* Discount
* Rating

---

# 🔹 Task 1: Data Cleaning & Visualization

## ✔ What was done:

* Handled missing values using mean/appropriate methods
* Removed duplicates
* Created new column: `Total_Amount = Price × Quantity`
* Performed basic visualizations

## 📊 Key Visualizations:

* Product Category Distribution
* Sales by Category
* Customer Demographics

## 🎯 Outcome:

Clean and structured dataset ready for analysis and modeling.

---

# 🔹 Task 2: Predictive Modeling

## ✔ Objective:

Predict whether a customer is a **High Spender**

## ✔ Steps:

* Created target column:

  * `High_Spender = 1 if Total_Amount > 10000 else 0`
* Encoded categorical data using LabelEncoder
* Split dataset using **stratified sampling**
* Trained models:

  * Decision Tree Classifier
  * Random Forest Classifier

## 📈 Evaluation:

* Accuracy Score
* Confusion Matrix

## 🎯 Outcome:

* Built and evaluated machine learning models
* Understood importance of proper data splitting

---

# 🔹 Task 3: Exploratory Data Analysis (EDA)

## ✔ Objective:

Analyze data to uncover patterns and trends

## ✔ Analysis Performed:

* Statistical summaries (`describe()`)
* Distribution analysis (Age, Price)
* Category analysis (Product_Category)
* Correlation heatmap
* High spender behavior analysis

## 📊 Key Insights:

* Customers aged 20–40 dominate purchases
* Electronics category has highest sales
* High spenders contribute major revenue
* Strong correlation between Price and Total_Amount
* Metro cities show higher spending patterns

## 🎯 Outcome:

* Identified trends and patterns
* Improved analytical thinking

---

# 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# 🚀 Project Structure

```
├── data/
│   └── retail_smart_store.csv
|   └──  Task1_DataCleaning.ipynb
│
├── notebookas2/
│   └── Task2_ML_Model.ipynb
│
├── notebook_3/
│   └── Task3_EDA.ipynb
├── README.md
```

---

# 📌 Conclusion

This project demonstrates:

* Data cleaning and preprocessing
* Data visualization and analysis
* Machine learning model building
* Insight generation for business decisions

---

# 🔥 Future Improvements

* Use larger dataset
* Apply advanced models (XGBoost, Neural Networks)
* Deploy model using Flask/Streamlit

---

# 👨‍💻 Author

**Nishanth Shekar T**
