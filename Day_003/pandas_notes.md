# Pandas Notes

## 📖 Introduction

Pandas is one of the most popular Python libraries for data analysis and data manipulation.

It provides powerful data structures that make working with structured data simple and efficient.

Pandas is widely used in:

- Data Analysis
- Machine Learning
- Data Science
- Artificial Intelligence
- Data Cleaning
- Data Preprocessing

---

# 🚀 Why Pandas?

Pandas helps us:

- Read data from files
- Organize data into tables
- Clean missing values
- Analyze data
- Filter rows and columns
- Generate statistical summaries

Without Pandas, performing these tasks would require much more code.

---

# 📦 Installing Pandas

```python
pip install pandas
```

---

# 📥 Importing Pandas

```python
import pandas as pd
```

`pd` is the standard alias used by Python developers.

---

# 📊 Series

A **Series** is a one-dimensional labeled array.

It stores a single column of data.

### Example

```python
import pandas as pd

marks = pd.Series([85, 90, 95, 80])

print(marks)
```

Output

```
0    85
1    90
2    95
3    80
dtype: int64
```

---

# 📋 DataFrame

A **DataFrame** is a two-dimensional table consisting of rows and columns.

It is the most commonly used data structure in Pandas.

### Example

```python
student = {
    "Name": ["Rohan", "Rahul", "Amit"],
    "Age": [22, 23, 21]
}

df = pd.DataFrame(student)

print(df)
```

Output

```
    Name   Age
0  Rohan   22
1  Rahul   23
2   Amit   21
```

---

# 📂 Reading a CSV File

CSV stands for **Comma-Separated Values**.

Pandas provides the `read_csv()` function to load CSV files.

### Syntax

```python
df = pd.read_csv("iris.csv")
```

---

# 👀 head()

The `head()` function displays the first five rows of a dataset.

```python
df.head()
```

You can also display a custom number of rows.

```python
df.head(10)
```

---

# 👇 tail()

The `tail()` function displays the last five rows.

```python
df.tail()
```

Example:

```python
df.tail(3)
```

---

# 📏 shape

The `shape` attribute returns the number of rows and columns.

```python
print(df.shape)
```

Example Output

```
(150, 5)
```

Meaning:

- 150 Rows
- 5 Columns

---

# ℹ️ info()

The `info()` function provides:

- Total rows
- Total columns
- Data types
- Non-null values
- Memory usage

```python
df.info()
```

---

# 📈 describe()

The `describe()` function provides statistical information.

```python
df.describe()
```

It includes:

- Count
- Mean
- Standard Deviation
- Minimum
- Maximum
- 25%
- 50%
- 75%

---

# ❓ Missing Values

Missing values are empty or null values in a dataset.

To check them:

```python
df.isnull().sum()
```

Example Output

```
SepalLength    0
SepalWidth     0
PetalLength    0
PetalWidth     0
Species        0
```

---

# 📌 Useful Pandas Functions

| Function | Purpose |
|----------|---------|
| read_csv() | Read CSV file |
| head() | First rows |
| tail() | Last rows |
| shape | Dataset dimensions |
| info() | Dataset information |
| describe() | Statistical summary |
| columns | Display column names |
| dtypes | Display data types |
| size | Total elements |
| isnull() | Detect missing values |
| sum() | Sum values |

---

# 🌍 Real-World Applications

Pandas is used in:

- Data Cleaning
- Machine Learning
- Business Analytics
- Finance
- Healthcare
- Banking
- E-commerce
- Research
- Artificial Intelligence

---

# 🎯 Interview Questions

## 1. What is Pandas?

Pandas is an open-source Python library used for data manipulation, analysis, and preprocessing.

---

## 2. What is a Series?

A Series is a one-dimensional labeled array that stores a single column of data.

---

## 3. What is a DataFrame?

A DataFrame is a two-dimensional table made up of rows and columns. It is the primary data structure used in Pandas.

---

## 4. Why do we use Pandas?

We use Pandas because it makes it easy to:

- Read datasets
- Clean data
- Analyze data
- Handle missing values
- Prepare data for Machine Learning

---

## 5. Difference between Series and DataFrame

| Series | DataFrame |
|--------|-----------|
| One-dimensional | Two-dimensional |
| Single column | Multiple columns |
| Stores one type of data | Stores structured tabular data |

---

## 6. What is the difference between head() and tail()?

| head() | tail() |
|---------|---------|
| Displays first rows | Displays last rows |

---

## 7. What is the difference between info() and describe()?

| info() | describe() |
|----------|-------------|
| Dataset structure | Statistical summary |
| Data types | Mean |
| Non-null values | Standard deviation |
| Memory usage | Min, Max, Quartiles |

---

# 📝 Summary

Today I learned the basics of **Pandas**, one of the most important libraries in Python for data analysis and machine learning.

Key concepts covered:

- Pandas
- Series
- DataFrame
- Reading CSV files
- head()
- tail()
- shape
- info()
- describe()
- Missing Values

I also explored the **Iris Dataset**, inspected its structure, checked for missing values, and generated a statistical summary. These are essential preprocessing steps before building Machine Learning models.