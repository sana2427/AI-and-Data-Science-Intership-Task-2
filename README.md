#  Task 2: Exploring and Visualizing a Simple Dataset

##  Overview
This repository contains the solution for **Task 2: Exploring and Visualizing a Simple Dataset**, completed as part of my **AI & Data Science Internship** tasks.

---

##  Objective
The objective of this task is to understand how to read, summarize, and visualize a dataset using Python. By applying exploratory data analysis techniques, we aim to identify patterns, distributions, relationships, and variations within the data before applying any machine learning models.

---

##  Dataset Description

**Dataset Name:** Iris Dataset  

The Iris dataset contains **150 samples** of iris flowers from **three species**:
- Iris setosa  
- Iris versicolor  
- Iris virginica  

### Features (Numerical – in centimeters):
- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`

### Target Variable:
- `species` (flower category)

The dataset is clean, balanced, and well-structured, making it ideal for practicing exploratory data analysis.

---

##  Tools & Libraries Used

- Python  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  

---

##  Approach

### 1️⃣ Data Loading & Inspection
- Loaded the dataset using `pandas.read_csv()`
- Inspected dataset structure using:
  - `.shape`
  - `.columns`
  - `.head()`
  - `.info()`

### 2️⃣ Data Cleaning & Preparation
- Checked for missing values
- Verified duplicate records
- Ensured data quality and consistency

### 3️⃣ Data Summarization
- Generated statistical summaries using `.describe()`
- Analyzed class distribution using `value_counts()`

### 4️⃣ Exploratory Data Analysis (EDA)
The following visualizations were created:
- **Scatter Plot** – to analyze relationships between variables
- **Histogram** – to examine data distribution
- **Box Plot** – to detect outliers and understand data spread

### 5️⃣ Model Training & Testing
- Applied **Logistic Regression** as a baseline classification model
- Split the dataset into training and testing sets (80/20 split)

### 6️⃣ Evaluation Metrics
- Accuracy Score  
- Confusion Matrix  

---

##  Results & Key Insights

- The dataset contains no missing values and is perfectly balanced
- Clear separability between species is visible through visualizations
- Petal features are more discriminative than sepal features
- Logistic Regression achieved high accuracy
- Exploratory Data Analysis provided strong insights into feature behavior

---

##  Conclusion

This task demonstrates the complete workflow of exploratory data analysis using Python. By visualizing and summarizing the dataset, meaningful insights were obtained that support effective model building in later stages.

---



