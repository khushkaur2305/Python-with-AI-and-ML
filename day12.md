# 📘 Day 12  

## ✅ Topic Covered
Introduction to **Pandas Library** and Data Manipulation in Python  

## 🧠 Summary
Today’s session focused on understanding **Pandas**, a **powerful Python library for data analysis and manipulation**. We explored:

- Importing Pandas using `import pandas as pd`  
- Understanding **Series** and **DataFrame** objects  
- Creating DataFrames from dictionaries, lists, and CSV files  
- Accessing and manipulating data using **indexing, slicing, and filtering**  
- Using built-in Pandas functions for **summary statistics, sorting, and aggregation**  
- Handling **missing data** using `isna()`, `fillna()`, and `dropna()`  

Pandas helps in **efficiently working with structured data**. Analogies helped: think of a **DataFrame as a spreadsheet** and Series as a **single column in the spreadsheet**.  

---

## 🧪 Examples & Concepts Practiced

| Concept/Feature          | Example                                           | Purpose/Use Case                             |
|--------------------------|--------------------------------------------------|---------------------------------------------|
| Import Library           | `import pandas as pd`                             | Access Pandas functionality                  |
| Series Creation           | `s = pd.Series([1,2,3,4])`                       | Create a single column of data               |
| DataFrame Creation        | `df = pd.DataFrame(data)`                         | Create a table with rows and columns        |
| Access Columns            | `df['column_name']`                               | Retrieve specific column data                |
| Access Rows               | `df.loc[0]`, `df.iloc[0]`                         | Retrieve rows by label or index              |
| Filtering                 | `df[df['age'] > 20]`                              | Filter rows based on conditions              |
| Summary Statistics        | `df.describe()`, `df.mean()`                       | Understand data distribution                 |
| Sorting                   | `df.sort_values('age')`                            | Organize data in ascending/descending order |
| Handling Missing Data     | `df.isna()`, `df.fillna(0)`, `df.dropna()`        | Detect, replace, or remove missing values   |
| Read/Write CSV            | `pd.read_csv('file.csv')`, `df.to_csv('file.csv')`| Load and save structured data                |

---

## 🔍 New Concepts Learned
- Pandas simplifies **data manipulation** for structured data.  
- DataFrames allow **tabular representation** similar to Excel.  
- Series represents **single-dimensional labeled data**, while DataFrame is **2-dimensional**.  
- Functions like `describe()`, `mean()`, `sum()`, and `value_counts()` provide quick insights.  
- Handling missing data is critical for accurate analysis.  

---

## 💻 Activity
- Imported Pandas and created Series and DataFrames.  
- Loaded sample CSV files and explored data using head, tail, and info functions.  
- Accessed, filtered, and sorted data.  
- Performed basic aggregation and summary statistics.  
- Detected and handled missing data using `fillna()` and `dropna()`.  

---

## 🤔 Challenges Faced
Understanding the **difference between `loc` and `iloc`** and handling missing values required careful practice.  

---

## 🎯 Key Takeaway
Pandas is **essential for data analysis**, enabling efficient manipulation, filtering, aggregation, and cleaning of structured data.  

---

## 📈 Understanding Today: 9/10  

---

