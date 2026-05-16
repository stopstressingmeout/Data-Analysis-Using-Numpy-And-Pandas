# Data Analysis Using Pandas and NumPy

## 📌 Project Overview
This project demonstrates fundamental **data analysis and manipulation techniques** using **Python**, **NumPy**, and **Pandas**.  
A synthetic employee dataset is created, saved as a CSV file, and then analyzed step-by-step using both NumPy arrays and Pandas DataFrames.

The notebook is designed to showcase:
- Data creation
- File handling
- Array operations
- DataFrame exploration
- Filtering, sorting, and updating data

---

## 🛠️ Tools & Libraries Used
- Python 3
- NumPy
- Pandas
- Jupyter Notebook / Google Colab

---

## 📂 Dataset Description
The dataset `employees.csv` is programmatically generated and contains **10 employee records** with the following columns:

| Column | Description |
|------|------------|
| id | Unique employee ID |
| age | Employee age |
| salary | Employee salary |
| dept | Department (HR, IT, Finance, Sales) |

---

## 🔹 Step 1: Data Creation
- Random employee ages and salaries are generated using NumPy.
- A Pandas DataFrame is created.
- The DataFrame is saved as **employees.csv**.

---

## 🔹 Step 2: Loading & Exploring Data
- The CSV file is loaded into a Pandas DataFrame.
- First 5 rows are displayed using `head()`.
- Dataset structure and data types are checked using `info()`.
- Summary statistics are generated using `describe()`.

---

## 🔹 Step 3: NumPy Array Operations
The `age` and `salary` columns are converted into NumPy arrays and analyzed.

### Operations performed:
- Data type, shape, dimension, and size checks
- Maximum and minimum salary
- Average salary and average age
- Total salary expense
- Salary range (difference between max and min)
- Age increment by 5 years
- Boolean filtering for employees older than 30

---

## 🔹 Step 4: Data Filtering & Selection (Pandas)
- Selected specific columns (`id`, `age`, `salary`)
- Displayed the last 3 rows
- Filtered employees working in the **IT department**
- Counted total IT employees

---

## 🔹 Step 5: Sorting & Ranking
- Sorted employees by salary in **descending order**
- Displayed the **top 3 highest-paid employees** along with:
  - Department
  - Age
  - Salary

---

## 🔹 Step 6: Data Updating Using `.loc`
- Replaced all salary values **greater than 80,000** with **80,000**
- Calculated the **new average salary** after replacement

---

## 📊 Key Insights
- Average employee age: **38.5 years**
- Original average salary: **57,446.9**
- New average salary after capping: **55,863.3**
- Total IT employees: **3**
- Highest original salary: **89,735**
- Total salary expense: **574,469**

