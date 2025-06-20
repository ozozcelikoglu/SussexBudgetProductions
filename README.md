
## SussexBudgetProductions – Budget Analysis Project

This repository contains a comprehensive data analysis project based on budgeting data provided by SussexBudgetProductions. The aim of this project was to explore spending patterns, identify inefficiencies, and provide data-driven recommendations for better financial planning. The entire process was conducted as part of a university-level Data Science coursework.

This documentation is written in a way that is accessible to non-technical readers, including those who may have no prior experience with data science or programming.

---

### Project Overview

SussexBudgetProductions is assumed to be an organization that tracks various types of expenses such as salaries, equipment, operational costs, and project expenditures. Over time, the budgeting data has accumulated in spreadsheet format (e.g., Excel files), but it is not easy to interpret or use this data directly to make informed decisions.

The goal of this project is to transform that raw, unstructured data into clear insights that answer questions such as:

- Which departments or activities tend to go over budget?
- Are there areas where spending could be reduced or optimized?
- What trends can be observed over time in specific cost categories?

---

### Project Structure

The repository is organized into the following folders:

```
SussexBudgetProductions-Analysis/
│
├── data/           → Raw data files and cleaned datasets
├── notebook/       → Python-based Jupyter Notebooks used for analysis
├── report/         → Final report with written interpretation and results
```

---

### 1. Data Preparation

The data was initially provided in spreadsheet format (Excel). It contained various inconsistencies such as missing values, merged cells, and inconsistent column names.

To prepare the data:

- Unnecessary rows and columns were removed.
- Columns were renamed for clarity.
- Missing or invalid entries were cleaned or imputed where appropriate.
- A standardized structure was applied to enable automated analysis.

---

### 2. Exploratory Data Analysis (EDA)

After the data was cleaned, exploratory analysis was conducted to understand the characteristics of the dataset. This included:

- Grouping expenses by department and category.
- Calculating total and average expenditures over time.
- Identifying maximum and minimum spending points.
- Investigating the distribution of costs using summary statistics and charts.

---

### 3. Data Visualization

To make the findings accessible and interpretable:

- Bar charts were used to show department-wise spending comparisons.
- Line graphs displayed how costs evolved across months or years.
- Pie charts illustrated the proportion of total budget allocated to each category.
- Tables summarized the top overspending or underspending departments.

These visualizations helped highlight anomalies and patterns that would be difficult to detect by reviewing raw numbers.

---

### 4. Key Insights

Some of the important findings from the project include:

- Certain departments had consistent overspending compared to the allocated budget.
- A few categories (e.g., marketing or logistics) showed high variability in spending from one period to another.
- There were redundant cost items that appeared across multiple departments without clear justification.
- Opportunities were identified where reallocation of funds could lead to more efficient resource use.

---

### 5. Recommendations

Based on the analysis, the following recommendations were made:

- Review budget allocations for departments with repeated overspending to understand operational constraints.
- Standardize and monitor recurring expenses to reduce redundancy.
- Use past spending data to forecast future budgets more accurately.
- Implement periodic reviews of financial reports with data visualizations to support managerial decision-making.

---

### 6. Technologies Used

Although the technical tools were used in the background, no technical knowledge is required to understand the report. For transparency:

- Python was used for data processing and analysis.
- Pandas library helped with organizing and summarizing the data.
- Matplotlib and Seaborn libraries were used to generate charts and graphs.
- Jupyter Notebook served as an interactive environment to combine code, visual outputs, and explanatory text.
- Final results were compiled into a written report using Microsoft Word or PDF format.

---

### How to Access the Work

There are two main ways to explore the work in this project:

- If you are not familiar with coding or Jupyter Notebooks, simply open the report located in the `/report` folder. This document summarizes all the findings and includes visuals with plain-English explanations.

- If you are comfortable with technical tools and wish to see how the analysis was done, open the Jupyter Notebook file in the `/notebook` folder using JupyterLab, Jupyter Notebook, or any compatible environment.

---

### Author

Öznur Özçelikoglu  
MSc in Data Science  
[LinkedIn Profile](https://www.linkedin.com/in/oznurozcelikoglu/)  
Email: ozcelikogluoznur@yahoo.com
