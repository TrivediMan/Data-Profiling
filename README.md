# 📊 PR1 – Data Profiler

A practical data analysis and data profiling project developed using Python and Jupyter Notebook. This project covers important concepts of data analysis, data science project planning, machine learning problem formulation, tensors, and working with different data sources such as CSV, JSON, SQLite databases, and APIs.

## 📌 Project Overview

The **PR1 Data Profiler** notebook demonstrates the basic workflow of working with data, from understanding and loading datasets to exploring their structure and preparing them for analysis.

The notebook contains both theoretical explanations and practical Python implementations using datasets such as sales data, school data, Titanic data, and customer churn data.

## 🎯 Objectives

* Understand the fundamentals of data analysis.
* Learn the major steps involved in a data science project.
* Understand machine learning problem statements.
* Learn about tensors and their dimensions.
* Load and inspect data from different sources.
* Perform basic data profiling and exploration.
* Work with structured and semi-structured data.
* Use Python libraries for data analysis and visualization.

## 📚 Topics Covered

### 1. Data Analysis

The notebook explains the complete data analysis process:

* Data Collection
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Data Transformation
* Modeling
* Interpretation
* Communication

It also covers four common types of analysis:

* Descriptive Analysis
* Diagnostic Analysis
* Predictive Analysis
* Prescriptive Analysis

### 2. Data Science Project Planning

The project planning section explains how to structure a data science project, including:

* Defining the business problem
* Setting project objectives
* Identifying stakeholders
* Collecting data
* Understanding and exploring data
* Data preparation
* Model planning
* Model building
* Model evaluation
* Deployment
* Monitoring
* Documentation

### 3. Machine Learning Problem Statement

The notebook includes a customer churn prediction problem based on purchase behaviour.

The problem is treated as a **Supervised Learning – Binary Classification** problem, where customer attributes are used to predict whether a customer will churn.

Example features include:

* Recency
* Frequency
* Monetary value
* Average order value
* Tenure
* Product variety
* Website visits
* Days since last login

Evaluation concepts include:

* Precision
* Recall
* F1-Score
* ROC-AUC
* PR-AUC

### 4. Tensors and NumPy

The notebook explains tensors as multi-dimensional numerical arrays and demonstrates:

* Scalars
* Vectors
* Matrices
* 3-D tensors
* Rank
* Shape
* Axis
* Data type

NumPy examples are used to create and display tensors of different dimensions.

## 🗂️ Data Sources Used

The notebook demonstrates working with multiple data formats and sources.

### CSV

A Titanic dataset is loaded using Pandas:

```python
df_csv = pd.read_csv("titanic.csv")
```

### JSON

A school dataset containing school and student information is loaded from a JSON file.

Example information includes:

* Student ID
* Name
* Gender
* Age
* Class
* Section
* Attendance
* Subject marks
* Fee status
* Transport
* Admission year

### SQLite Database

Sales data is retrieved from a SQLite database using SQL and Pandas:

```python
conn = sqlite3.connect("sales_random_data.db")

res = pd.read_sql_query("SELECT * FROM Sales;", conn)
```

The sales dataset contains fields such as:

* Order ID
* Order Date
* Customer
* Product
* Category
* Quantity
* Unit Price
* Discount
* Sales
* Region
* Payment Method

The demonstrated sales table contains **1,000 rows and 11 columns**.

### API

The notebook also demonstrates retrieving image data from the Pixabay API using the `requests` library.

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Requests**
* **SQLite**
* **JSON**
* **SQL**

The notebook imports Pandas, NumPy, Matplotlib, Seaborn, Requests, and SQLite for its practical work.

## 📁 Project Structure

```text
PR1-Data-Profiler/
│
├── PR1 Data Profiler(2).ipynb
├── titanic.csv
├── school_random_data.json
├── sales_random_data.db
└── README.md
```

> File names may need to be adjusted according to the files included in the GitHub repository.

## 🔍 Data Profiling

Data profiling is used to understand the structure and quality of a dataset before performing deeper analysis.

Typical profiling activities include:

* Checking dataset dimensions
* Inspecting column names
* Checking data types
* Finding missing values
* Checking duplicate records
* Reviewing numerical statistics
* Understanding categorical columns
* Identifying unusual or inconsistent values

The notebook also demonstrates inspecting a customer dataset containing **1,000 records and 7 columns**, including customer, age, income, purchase, gender, churn, and date.

## ▶️ How to Run

1. Install Python.
2. Install Jupyter Notebook or JupyterLab.
3. Clone or download this repository.
4. Keep the required datasets in the appropriate project directory.
5. Open the notebook:

```bash
jupyter notebook
```

6. Open:

```text
PR1 Data Profiler.ipynb
```

7. Run the notebook cells sequentially.

## 💻 Installation

Install the main Python libraries using:

```bash
pip install pandas numpy matplotlib seaborn requests
```

SQLite support is available through Python's built-in `sqlite3` module.

## 📈 Learning Outcomes

After completing this project, you should be able to:

* Explain the data analysis process.
* Understand the stages of a data science project.
* Define a machine learning problem statement.
* Understand basic tensor concepts.
* Load data from CSV and JSON files.
* Query data from SQLite databases.
* Work with APIs using Python.
* Inspect and profile datasets.
* Use Pandas and NumPy for data manipulation.
* Understand basic exploratory data analysis.

## 🚀 Future Improvements

The project can be extended by adding:

* Automated data profiling reports
* More EDA visualizations
* Missing-value treatment
* Outlier detection
* Correlation analysis
* Feature engineering
* Machine learning model training
* Model evaluation dashboards
* Interactive visualizations

## 📝 Conclusion

**PR1 – Data Profiler** provides a practical introduction to data analysis and data profiling using Python. It combines theoretical concepts with hands-on examples involving different datasets and data sources.

The project helps build a foundation for understanding how data is collected, inspected, explored, transformed, and prepared for further analysis and machine learning.

---

### 👨‍💻 Project

**Project Name:** PR1 – Data Profiler
**Notebook:** `PR1 Data Profiler.ipynb`
**Domain:** Data Analysis & Data Science
**Language:** Python
**Author:** Man Trivedi
