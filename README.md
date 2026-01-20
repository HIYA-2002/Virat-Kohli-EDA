# Virat Kohli ODI Batting Performance – Exploratory Data Analysis

## 📌 Project Overview
This project performs an exploratory data analysis (EDA) on Virat Kohli’s ODI batting
performance to uncover scoring patterns, consistency, and key performance drivers using Python.

The analysis focuses on understanding how factors such as balls faced, 
strike rate, boundary contribution, batting position, and opposition influence run scoring.

---

## 🎯 Objectives
- Analyze run distribution and scoring consistency
- Examine the relationship between runs, balls faced, and strike rate
- Understand the impact of boundaries on total runs
- Study performance variation across batting positions and oppositions
- Identify key performance drivers using correlation analysis

---

## 📂 Dataset Description
The dataset contains match-wise ODI batting statistics of Virat Kohli, where 
each row represents a single innings.  
Key columns include:
- Runs
- Balls Faced (BF)
- Strike Rate (SR)
- Fours (4s) and Sixes (6s)
- Batting Position
- Dismissal Type
- Opposition
- Ground
- Match Date

---

## 🧹 Data Cleaning
- Checked for missing values and duplicate records
- Converted date columns to datetime format
- Ensured correct data types for numerical columns
- Created derived features for better analysis

---

## 📊 Analysis Performed
### Univariate Analysis
- Runs distribution
- Balls Faced distribution
- Strike rate distribution
- Boundary contribution
- Batting position frequency
- Dismissal type distribution

### Bivariate Analysis
- Runs vs Balls Faced
- Runs vs Strike Rate
- Batting Position vs Runs
- Batting Position vs Strike Rate
- Boundaries vs Runs
- Boundaries vs Strike Rate
- Opposition vs Average Runs

### Multivariate Analysis
- Runs vs Balls Faced by batting position
- Runs vs Strike Rate with boundary contribution
- Performance comparison across oppositions

### Correlation Analysis
- Heatmap showing relationships between key batting metrics

---

## 🔍 Key Insights
- Higher scores are strongly associated with spending more time at the crease.
- Boundary hitting supports scoring but is not the sole contributor to high runs.
- Strike rate varies with match context and does not solely define performance.
- Batting performance remains consistent across positions.
- Performance varies across oppositions, reflecting contextual adaptability.

---

## 🏁 Conclusion
This project highlights that Virat Kohli’s ODI batting success is driven more by consistency
and innings construction than pure aggression. The analysis demonstrates how exploratory data
analysis can be used to derive meaningful insights from real-world sports data.

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Files in Repository
- `Virat_Kohli_EDA.ipynb` – Main analysis notebook
- `Virat Kohli ODI Batting Performance.pdf` – Project report
- (`Virat Kohli Dataset.csv`) - Dataset file 

---

## 📬 Contact
For any queries or feedback, feel free to connect.
