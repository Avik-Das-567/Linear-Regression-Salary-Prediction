# Linear Regression with Streamlit - Salary Prediction
### App Link
- https://linear-regression-salary-prediction.streamlit.app/
---
### What is Linear Regression?
- Linear Regression is a **math method** used to **predict numbers**.
- It draws a **straight line** through data points.
- It helps **understand relationships** between two or more things.
---
### Required Python Packages
- **`scikit-learn`** - To build machine learning models
- **`streamlit`** - To build data apps
- **`pandas`** - To work with the dataset
---
### Example Problem
- Predicting **Salary** Based on **Experience** and **Age**
- We have data about **Experience in Years**, **Age**, and **Salary in Thousands**.

| Experience\_in\_Years | Age | Salary\_in\_Thousands |
| --------------------- | --- | --------------------- |
| 1                     | 22  | 30                    |
| 2                     | 24  | 40                    |
| 3                     | 26  | 50                    |
| 4                     | 28  | 60                    |
| 5                     | 30  | 70                    |

---
### How It Works
- **Load the data** using **`pd.read_csv()`**.
- **Train a model** using **`LinearRegression()`**.
- Ask for **user inputs** for both experience and age.
- **Show the result** using **`st.write()`**.
---
