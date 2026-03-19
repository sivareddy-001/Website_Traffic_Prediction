# 📊 Website Traffic Prediction using Polynomial Regression

## 📌 Project Overview

This project focuses on analyzing and predicting website traffic using **Polynomial Regression**.
The dataset represents daily website analytics data for the year **2025**, including key metrics such as sessions, bounce rate, pages per session, and visitors.

The goal of this project is to build a machine learning model that can **predict the number of visitors** based on user engagement metrics.

---

## 📂 Dataset Description

The dataset contains **365 rows (daily data for 2025)** with the following columns:

| Column Name | Description                                          |
| ----------- | ---------------------------------------------------- |
| Date        | Date of recorded website activity                    |
| Sessions    | Number of visits to the website                      |
| Bounce_Rate | Percentage of users who leave after viewing one page |
| Pages       | Average pages viewed per session                     |
| Visitors    | Number of unique visitors                            |

---

## 🎯 Objective

* Analyze website traffic behavior
* Understand relationships between engagement metrics
* Predict **Visitors** using:
  * Sessions
* Apply **Polynomial Regression** to capture non-linear patterns

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## ⚙️ Machine Learning Approach

### 1. Data Preprocessing

* Loaded dataset using Pandas
* Selected relevant features (Sessions, Pages)
* Defined target variable (Visitors)

### 2. Train-Test Split

* Split dataset into training and testing sets (80/20)

### 3. Polynomial Feature Transformation

* Converted features into polynomial features (degree = 2)

### 4. Model Training

* Used **Linear Regression** on transformed polynomial features

### 5. Prediction

* Predicted visitor count using trained model

### 6. Evaluation

* Evaluated model using **R² Score**

---

## 📈 Model Formula

Polynomial Regression equation:

[
Visitors = b_0 + b_1(Sessions) + b_2(Pages) + b_3(Sessions^2) + b_4(Sessions \cdot Pages) + b_5(Pages^2)
]

---

## 📊 Visualization

* Scatter plot of actual data (Sessions vs Visitors)
* Polynomial regression curve showing non-linear relationship

---

## 🚀 How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/your-username/website-traffic-polynomial-regression.git
```

2. Navigate to the project folder:

```bash
cd website-traffic-polynomial-regression
```

3. Install dependencies:

```bash
pip install pandas numpy matplotlib scikit-learn
```

4. Run the Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📌 Sample Prediction

Input:

* Sessions = 500

Output:

* Predicted Visitors ≈ 400+

---

## 📊 Key Insights

* Higher sessions generally lead to more visitors
* Increased pages per session indicates better engagement
* Polynomial regression captures **non-linear growth patterns** better than linear models

---

## 🔮 Future Improvements

* Add more features like traffic source and session duration
* Compare with Linear Regression and other models
* Deploy model using Flask or Streamlit
* Perform time-series forecasting

---

## 👨‍💻 Author

**Siva Reddy**
Aspiring Data Analyst

---

## ⭐ Conclusion

This project demonstrates how Polynomial Regression can be effectively used to model and predict website traffic patterns. It highlights the importance of feature relationships and non-linear modeling in real-world data analysis.

---

⭐ If you found this project useful, feel free to star the repository!
