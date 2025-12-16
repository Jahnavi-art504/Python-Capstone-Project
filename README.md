<img width="857" height="185" alt="image" src="https://github.com/user-attachments/assets/5f032520-1b15-497f-9d5c-10f2e0de8e60" />

## 📑 Table of Contents
Project Overview
Dataset Descriptions
Environment Setup
File Structure
Task Breakdown
Methodology & Implementation
Results & Deliverables
How to Run
Technologies Used
Contributing
License
Author
Screenshots

## 1 Project Overview
“Data is the new oil — but only when it’s refined.”
This capstone refines three raw datasets into business-ready insights.
You’ll see ten incremental tasks that illustrate core skills every data-analyst needs:
ingestion, cleaning, merging, conditional logic, aggregation, and filtered reporting.

## 2 Dataset Descriptions
📄 DataFrame	Columns (key)	Description
Employee	ID · Name · Gender · City · Age	Personal & location data
Seniority	ID · Designation Level (1–4)	Role hierarchy
Project	ID · Project · Project Cost · Status	Budget & completion status

## 3 Environment Setup
Python ≥3.7 recommended pip install pandas numpy notebook

text

## 4 File Structure
Python-Capstone-Project/ │ ├─ Capstone_Project_Python.ipynb # notebook with all tasks ├─ data/ │ ├─ employee.csv │ ├─ seniority.csv │ ├─ project.csv │ ├─ final_temp.csv │ ├─ total_project_cost.csv │ └─ final_dataframe.csv └─ screenshots/ ├─ task1.png ├─ task2.png └─ … one per task

text

## 5 Task Breakdown
#	Task	Key Action
1	Create CSVs	Build & persist Employee, Seniority, Project tables
2	Impute Costs	Replace missing Project Cost with a running average
3	Split Names	Separate First / Last & drop the composite column
4	Merge	Combine all tables into Final
5	Bonus	+5 % cost for Finished projects
6	Demotion	↓ designation for any Failed project; drop ineligible leads
7	Titles	Add “Mr.” / “Mrs.” prefix, remove Gender
8	Promotion	↑ designation for age > 29 (min-clipped at 1)
9	Aggregation	Summarise total project cost per employee
10	City Filter	Display all rows where City contains “o”

## 6 Methodology & Implementation
Click to expand

## 7 Results & Deliverables
📁 File	Purpose
employee.csv	Cleaned employee data
seniority.csv	Original designation levels
project.csv	Imputed project table
final_temp.csv	Merged output (post-Task 8)
total_project_cost.csv	Per-employee cost summary
final_dataframe.csv	Filtered dataset for Task 10
Capstone_Project_Python.ipynb	Executable notebook

## 8 How to Run
Clone the repository.
Ensure the data folder contains all CSVs.
Launch Jupyter Notebook and open Capstone_Project_Python.ipynb.
Run all cells (Tasks 1 → 10).
Inspect the new / updated CSVs in data/.

## 9 Technologies Used
🐍 Python 3.x
🐼 pandas
📊 NumPy
📓 Jupyter Notebook

## 10 Contributing
Ideas & pull requests are welcome! Possible enhancements:

Parameterise the bonus percentage.
Visualise cost distributions.
Convert the notebook into a CLI script.

## 11 License
MIT – free to use, modify, and distribute.

## 12 Author
Deepak Lokhande — Data-Analytics Enthusiast | Business Intelligence | Remote-Work Advocate

## 13 Screenshots
### Task 1 – Create CSVs
### Task 2 – Impute Costs
### Task 3 – Split Names
### Task 4 – Merge DataFrames
### Task 5 – Add Bonus
### Task 6 – Demote / Prune
### Task 7 – Prefix Titles
### Task 8 – Promote Levels
### Task 9 – Total Cost Summary
### Task 10 – City Filter Output
