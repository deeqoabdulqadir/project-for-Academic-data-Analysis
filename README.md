# project-for-Academic-data-Analysis
Student Attendance and Academic Analysis

📊 Student Attendance and Academic Performance Analysis
📌 Project Overview

This project is an Excel Data Analysis project focused on analyzing student attendance, assignment performance, midterm scores, final scores, and academic status.

The project demonstrates the complete data analysis process in Microsoft Excel, including data cleaning, data validation, formula-based analysis, Pivot Tables, data visualization, and dashboard development.

The goal of this project is to transform raw student performance data into meaningful insights that can help identify academic performance patterns and students who may be at risk.

🎯 Project Objectives
Clean and prepare the original student dataset.
Identify missing and inconsistent data.
Analyze student attendance and academic performance.
Calculate key statistical measures using Excel formulas.
Use logical and conditional formulas for performance analysis.
Create Pivot Tables for summarizing the data.
Create charts and visualizations.
Develop an interactive academic performance dashboard.
Present important findings and KPIs in a professional format.
## 📂 Dataset

The dataset contains information about student academic performance.

### Main Variables

| Column               | Description                                   |
| -------------------- | --------------------------------------------- |
| Student_ID         | Unique identification number for each student |
| Program            | Student's academic program                    |
| Attendance_Percent | Student attendance percentage                 |
| Assignment_Score   | Assignment performance score                  |
| Midterm_Score      | Midterm examination score                     |
| Final_Score        | Final examination score                       |
| Academic_Status    | Student's academic performance status    

### Dataset Size

* *Original records:* 300 students
* *Original variables:* 7
* *Cleaned records:* 297 students
* *Cleaned variables:* 7
* *Missing cells identified:* 15
* *Duplicate records identified:* 3
  
## 🧹 Data Cleaning

The project includes a dedicated Clean_Data sheet where the original dataset was prepared for analysis.

The cleaning process included:

* Identifying missing values.
* Removing duplicate records.
* Handling inconsistent program names.
* Standardizing academic status values.
* Checking incorrect or unusual values.
* Preparing the dataset for formulas and Pivot Tables.
Examples of inconsistent values found in the original data include different forms of academic status such as:

* Good Standing
* good standing
* At Risk

Program values were also reviewed for inconsistencies such as abbreviated names.
## 🧮 Excel Analysis

The Analysis sheet contains formula-based analysis and data-quality checks.

The project demonstrates Excel functions such as:

* AVERAGE
* AVERAGEIF
* COUNT
* COUNTA
* COUNTIF
* MAX
* MIN
* IF
* OR
* Text-cleaning functions
* Logical analysis formulas
### Example Analysis

The project calculates:

* Total number of records
* Unique student IDs
* Average attendance
* Average assignment score
* Average midterm score
* Average final score
* Minimum final score
* Maximum final score
* Average final score by academic status
* Performance flags
## 📊 Pivot Tables

The PivotTables sheet summarizes the cleaned data using Pivot Tables.

The Pivot Tables are used to analyze:

* Number of students by program
* Academic status distribution
* Student performance
* Assignment performance
* Other summarized academic measures

Pivot Tables make it easier to compare different groups of students and identify patterns in the dataset.
## 📈 Dashboard

The Dashboard sheet presents the analysis visually through a *Student Academic Performance Dashboard*.

The dashboard is designed to provide a quick overview of student performance.

### Dashboard Components

* KPI cards
* Charts
* Academic status analysis
* Program-level analysis
* Student performance metrics
* Visual summaries
The dashboard helps users quickly understand the overall academic situation without manually examining the raw dataset.
## 🔍 Key Areas of Analysis

The project focuses on several important questions:

1. How many students are included in the dataset?
2. What is the average attendance percentage?
3. What is the average final score?
4. Which academic programs have the most students?
5. How many students are in *Good Standing*?
6. How many students are *At Risk*?
7. How does attendance relate to academic performance?
8. What are the minimum and maximum final scores?
9. Which students may require additional academic attention?

## 🛠️ Tools Used

* *Microsoft Excel*
* Excel Formulas
* Excel Tables
* Pivot Tables
* Pivot Charts
* Data Cleaning
* Data Analysis
* Data Visualization
* Dashboard Design

## 📁 Workbook Structure

text
Book1211.xlsx
│
├── Original data
│   └── Raw student performance dataset
│
├── Clean_Data
│   └── Cleaned and prepared dataset
│
├── Analysis
│   └── Formulas, statistics and quality checks
│
├── PivotTables
│   └── Pivot Table summaries
│
├── Dashboard
│   └── Student Academic Performance Dashboard
│
├── Sheet1
│   └── Supporting worksheet
│
└── Project-info
    └── Project information and documentation
