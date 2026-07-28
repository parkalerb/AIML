# Day 017 - Pandas Basics

## 📚 Overview

Welcome to **Day 017** of my AI & Machine Learning learning journey.

Today, I explored **Pandas**, one of the most widely used Python libraries for data analysis and preprocessing. I learned how to load a dataset, inspect its structure, analyze statistics, and identify missing values using Pandas.

This marks my first practical step toward Machine Learning data preprocessing.

---

# 🎯 Learning Objectives

- Understand the basics of Pandas
- Learn the difference between Series and DataFrame
- Read CSV files using Pandas
- Inspect a dataset
- Analyze dataset statistics
- Check missing values
- Prepare data for Machine Learning

---

# 📂 Folder Structure

```
Day_003/
│
├── pandas_basics.ipynb
├── pandas_notes.md
└── README.md
```

---

# 📖 Topics Covered

- Introduction to Pandas
- Series
- DataFrame
- Reading CSV Files
- `head()`
- `tail()`
- `shape`
- `info()`
- `describe()`
- Missing Values
- Dataset Inspection

---

# 💻 Practical Tasks Performed

## ✅ Loaded a CSV Dataset

Used the `read_csv()` function to load a dataset into a Pandas DataFrame.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")
```

---

## ✅ Displayed First Rows

Used:

```python
df.head()
```

Purpose:

- Preview the dataset
- Verify successful loading

---

## ✅ Displayed Last Rows

Used:

```python
df.tail()
```

Purpose:

- Inspect the end of the dataset

---

## ✅ Checked Dataset Shape

Used:

```python
df.shape
```

Purpose:

- Determine the number of rows and columns

---

## ✅ Viewed Dataset Information

Used:

```python
df.info()
```

Purpose:

- Display column names
- Data types
- Non-null values
- Memory usage

---

## ✅ Generated Statistical Summary

Used:

```python
df.describe()
```

Purpose:

- Count
- Mean
- Standard Deviation
- Minimum
- Maximum
- Quartiles

---

## ✅ Checked Missing Values

Used:

```python
df.isnull().sum()
```

Purpose:

- Detect empty or null values in each column

---

# 📈 Skills Gained

After completing today's practical, I learned how to:

- Import the Pandas library
- Load CSV files
- Work with DataFrames
- Explore dataset structure
- Generate statistical summaries
- Identify missing values
- Perform basic data inspection

---

# 🧠 Key Takeaways

- Pandas simplifies working with structured data.
- A DataFrame is the primary data structure used for tabular data.
- Data inspection is an essential step before building Machine Learning models.
- Checking missing values helps ensure data quality before preprocessing.

---

# 📊 Progress

| Topic | Status |
|--------|--------|
| Pandas Basics | ✅ Completed |
| Series | ✅ Completed |
| DataFrame | ✅ Completed |
| Read CSV | ✅ Completed |
| head() | ✅ Completed |
| tail() | ✅ Completed |
| shape | ✅ Completed |
| info() | ✅ Completed |
| describe() | ✅ Completed |
| Missing Values | ✅ Completed |

---

# 🚀 Technologies Used

- Python 3
- Pandas
- Jupyter Notebook
- Visual Studio Code
- Git
- GitHub

---

# 📌 What's Next?

In the next learning session, I will continue exploring more Pandas operations and begin working with additional data preprocessing techniques commonly used in Machine Learning.

---

# 👨‍💻 Author

**Rohan Parkale**

- MCA Student
- Python Developer
- AIML Enthusiast
- Passionate about Machine Learning, Data Science, and Software Development

---

⭐ Thank you for visiting this repository! Feel free to explore my other learning repositories and follow my AI & Machine Learning journey on GitHub.