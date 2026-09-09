# Codveda Data Analytics Internship - Projects Portfolio

This repository contains the completed tasks and projects for the Codveda Data Analytics Internship. Each level focuses on different tools and techniques ranging from data cleaning and ETL to advanced data modeling and visualization.

---

## 📁 Project Structure & Levels

### **Level 1: Fundamentals of Data Analysis**
* **Dataset:** Boston Housing / Exploratory Datasets
* **Tools Used:** Microsoft Excel
* **Overview:** Performed basic data exploration, sorting, filtering, and initial summary statistics to understand data distributions.

### **Level 2: Intermediate Data Cleaning & Transformation**
* **Dataset:** Housing & Real Estate Data
* **Tools Used:** Excel Power Query
* **Overview:** Built automated data pipelines, cleaned inconsistent text, handled missing values, changed data types, and restructured tables for analysis.

### **Level 3: Advanced Data Modeling, DAX, & Visualization**
* **Dataset:** Sentiment Dataset (`Sentiment dataset.csv`)
* **Tools Used:** Excel Power Pivot, Power Query, and DAX
* **Key Tasks Completed:**
  * **ETL (Power Query):** Loaded raw sentiment data, cleaned columns, and split the `Timestamp` column into distinct `Date` and `Time` features.
  * **Data Modeling (Power Pivot):** Established the data model and wrote custom DAX measures:
    * `Total Likes` = `SUM('Sentiment dataset'[Likes])`
    * `Avg Retweets` = `AVERAGE('Sentiment dataset'[Retweets])`
  * **Analysis & Visualization:** Created interactive Pivot Tables and a professional Pivot Chart to analyze sentiment distribution and engagement metrics across platforms.

---

## 🚀 How to Open and Run
1. Clone or download this repository to your local machine.
2. Open the respective `.xlsx` workbook files in Microsoft Excel.
3. *Note:* For Level 3, make sure to enable content/data model extensions if prompted so that the Power Pivot data model and DAX measures function properly.

---
*Created as part of the Codveda Internship Program.*
