# hcl-project
# Student Performance and Attendance Analysis

A Python-based project designed to manage student academic performance and attendance efficiently using Pandas and Excel/CSV datasets. Developed using Google Colab.

## Features
- Upload student datasets in CSV, XLSX, and XLS formats.
- Generate individual student performance reports.
- Calculate total marks and percentage.
- Identify best and improvement-needed subjects.
- Calculate class rankings and identify toppers.
- Classify attendance as Excellent, Good, or Average.
- Analyse subject-wise class averages.
- Generate comprehensive Excel reports with multiple sheets.

## Technologies Used
- Python
- Pandas
- Google Colab
- Excel / CSV

## Dataset Requirements
The dataset must contain these columns:
- Student_ID
- Student_Name
- Mathematics_Marks
- Physics_Marks
- Chemistry_Marks
- Attendance_%

Marks and attendance must be between 0 and 100. Student IDs must be unique.

## How to Run
1. Open the Python notebook in Google Colab.
2. Run the code cells.
3. Upload your student dataset when prompted.
4. Choose an option from the main menu.
5. View student reports or export the complete Excel report.

## Main Menu
1. View Individual Student Report
2. View Class Ranking
3. View Attendance Report
4. View Academic Performance Analysis
5. Export Complete Excel Report
6. Exit

## Output
The project generates an Excel workbook named `Student_Performance_Attendance_Report.xlsx` containing:
- Student_Data
- Class_Ranking
- Attendance_Report
- Attendance_Summary
- Subject_Averages
- Academic_Summary

## Installation
```bash
pip install pandas openpyxl
```

## Project Objective
To simplify student performance monitoring and attendance management through automated calculations, reports, and data analysis.

## Future Improvements
- Graphical dashboard for performance analysis.
- Student-wise progress charts.
- Database integration.
- Automated performance alerts.

## Author
Anvesha Anand
