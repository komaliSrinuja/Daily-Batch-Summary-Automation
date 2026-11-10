# Task Management Data Analysis and Daily Reporting

## 📌 Project Overview

This project performs task management data analysis using Python. It analyzes task details such as task status, priority, assigned employees, departments, and due dates to generate meaningful summaries and reports.

The project uses **Pandas** for data manipulation, **Matplotlib** for visualization, and Excel and text files for data storage and reporting.

## 🎯 Objectives

- Analyze task distribution across different departments.
- Track pending, completed, and in-progress tasks.
- Identify high-priority and critical pending tasks.
- Check datasets for duplicate records and missing values.
- Generate daily task summary reports.
- Export task data into Excel format.

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **Datetime** – Date handling and report generation
- **Excel** – Data storage and reporting

## 📊 Key Features

### 1. Task Data Creation
Created a sample dataset containing:
- Task ID
- Task Name
- Assigned To
- Department
- Status
- Priority
- Due Date

### 2. Excel Data Handling
- Exported task data into an Excel file.
- Read the exported Excel file using Pandas.
- Displayed records for analysis.

### 3. Task Status Analysis
Calculated:
- Total Tasks
- Pending Tasks
- Completed Tasks
- In-Progress Tasks
- High-Priority Tasks

### 4. Department-Wise Analysis
Grouped tasks by department to understand the distribution of work across teams.

### 5. Critical Task Identification
Filtered tasks based on two conditions:
- Status = Pending
- Priority = High

This helps identify tasks that may require immediate attention.

### 6. Data Quality Checks
- Checked for duplicate records.
- Identified missing or null values.

### 7. Daily Batch Summary Report
Generated a daily report containing task statistics and saved it as a text file.

### 8. Data Visualization
Created a bar chart to visualize the distribution of tasks by status.

## 📁 Project Files

- `Task_Management_Analysis.ipynb` – Python analysis notebook
- `backlog.xlsx` – Excel file containing task data
- `Daily_Batch_Report.txt` – Generated daily summary report

## ▶️ How to Run the Project

1. Clone this repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Navigate to the project folder:

   ```bash
   cd <project-folder>
   ```

3. Install the required libraries:

   ```bash
   pip install pandas matplotlib openpyxl
   ```

4. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the notebook and run all cells.

## 💡 Key Learning Outcomes

- Practical experience with Pandas DataFrames.
- Data filtering, grouping, and aggregation.
- Excel file reading and writing.
- Data quality validation.
- Conditional data analysis.
- Automated report generation.
- Data visualization using Matplotlib.

## 👩‍💻 Author

**Komali Srinuja**

