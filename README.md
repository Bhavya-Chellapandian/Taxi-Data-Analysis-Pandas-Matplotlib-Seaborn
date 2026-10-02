# 🚕 Taxi Data Analysis using Pandas, Matplotlib & Seaborn

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

This project performs **Taxi Data Analysis using Python** with **Pandas, Matplotlib, and Seaborn**.

The analysis covers data loading, missing-value handling, exploratory data analysis, statistical visualization, and advanced visualization techniques using the **Taxis dataset** available through Seaborn.

The project demonstrates how Python visualization libraries can be used to understand taxi trip patterns, fares, distances, payment methods, tips, and relationships between numerical variables.

---

## 🎯 Objectives

- Import and work with Python data analysis libraries
- Load the Taxis dataset using Seaborn
- Identify missing values
- Handle missing numerical and categorical values
- Analyze taxi fares and trip distances
- Explore trips by pickup borough and payment method
- Visualize relationships between distance, fare, tips, tolls, and total amount
- Apply basic, statistical, and advanced visualization techniques

---

## 🛠️ Technologies & Libraries

| Technology | Purpose |
|---|---|
| 🐍 Python | Programming & Data Analysis |
| 🐼 Pandas | Data Manipulation |
| 🔢 NumPy | Numerical Operations |
| 📊 Matplotlib | Data Visualization |
| 🎨 Seaborn | Statistical Visualization |
| 📓 Jupyter Notebook | Development Environment |

---

## 📂 Dataset

The project uses the built-in **Taxis dataset** provided by Seaborn.

```python
df = sns.load_dataset("taxis")
```

The dataset contains taxi trip-related information such as:

- Pickup time
- Pickup borough
- Pickup zone
- Distance
- Fare
- Tip
- Tolls
- Total
- Payment method

---

## 🔍 Data Analysis Workflow

### 1️⃣ Import Libraries

The following libraries are imported:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

### 2️⃣ Load Dataset

The Seaborn Taxis dataset is loaded into a Pandas DataFrame.

### 3️⃣ Missing Value Analysis

Missing values are identified using:

```python
df.isnull().sum()
```

Both missing counts and missing percentages are calculated.

### 4️⃣ Data Cleaning

Missing numerical values are filled using the **median**, while missing categorical values are filled using the **mode**.

This ensures that the dataset is prepared for visualization and analysis.

---

## 📊 Visualizations

### 📈 Basic Visualizations

The notebook includes:

- **Line Chart** – Fare Over Time
- **Bar Chart** – Total Fare by Pickup Borough
- **Pie Chart** – Trips by Payment Method
- **Histogram** – Taxi Trip Distance Distribution

### 📉 Statistical Visualizations

The project also uses Seaborn for:

- **Box Plot** – Tip Amount by Pickup Borough
- **Count Plot** – Number of Trips by Pickup Borough
- **Scatter Plot** – Distance vs Fare

### 🔥 Advanced Visualizations

The notebook includes:

- **Correlation Heatmap**
- **Pair Plot**
- **Violin Plot**

These visualizations provide deeper understanding of relationships and distributions within the taxi dataset.

---

## 📌 Key Analysis Areas

### 🚕 Fare Analysis
Examines taxi fares over time and compares total fare across pickup boroughs.

### 📍 Trip Analysis
Analyzes the number of taxi trips across different pickup boroughs.

### 💳 Payment Analysis
Explores the distribution of trips according to payment method.

### 📏 Distance Analysis
Studies the distribution of taxi trip distances.

### 💰 Tip Analysis
Uses box plots to examine tip distributions across pickup boroughs.

### 🔗 Relationship Analysis
The scatter plot and correlation heatmap investigate relationships among:

```text
Distance
Fare
Tip
Tolls
Total
```

---

## 📁 Project Structure

```text
Taxi-Data-Analysis/
│
├── Taxi_Data_Analysis_using_Pandas,_Matplotlib_&_Seaborn.ipynb
└── README.md
```

---

## ▶️ How to Run

### Option 1 — Google Colab

1. Open Google Colab.
2. Upload the `.ipynb` file.
3. Run the notebook cells sequentially.

### Option 2 — Jupyter Notebook

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Taxi_Data_Analysis_using_Pandas,_Matplotlib_&_Seaborn.ipynb
```

---

## 💡 Skills Demonstrated

- Python Programming
- Pandas Data Manipulation
- NumPy
- Data Cleaning
- Missing Value Handling
- Exploratory Data Analysis
- Data Visualization
- Statistical Visualization
- Matplotlib
- Seaborn
- Correlation Analysis
- Data Interpretation

---

## 👩‍💻 Author

**Bhavya C**

🎯 Aspiring Data Analyst

- GitHub: [Bhavya-Chellapandian](https://github.com/Bhavya-Chellapandian)
- LinkedIn: [Bhavya C](https://www.linkedin.com/in/bhavya-chellapandian)

---

## 🏷️ Tags

```text
#Python
#Pandas
#NumPy
#Matplotlib
#Seaborn
#DataAnalysis
#DataVisualization
#ExploratoryDataAnalysis
#EDA
#DataScience
#PythonProjects
#JupyterNotebook
#GoogleColab
#TaxiDataAnalysis
#DataAnalytics
#Analytics
#Visualization
```

### ⭐ Project Highlights

> **Clean Data → Analyze Patterns → Visualize Insights → Understand Relationships**

This project demonstrates a practical Python-based workflow for analyzing and visualizing taxi trip data.
