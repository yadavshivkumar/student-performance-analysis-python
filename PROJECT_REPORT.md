# Student Performance Analysis — Project Report

## 1. Introduction

Student Performance Analysis is a Python-based data analysis project that examines students' academic performance in Mathematics and Portuguese.

The project uses Pandas, NumPy, Matplotlib, and Seaborn to inspect datasets, calculate descriptive statistics, and visualize relationships between selected variables.

## 2. Problem Statement

Educational performance data contains information that can be analyzed to identify patterns in grades, study habits, and school attendance.

The purpose of this project is to explore these patterns and summarize the results using statistical measures and visualizations.

## 3. Objectives

- Load and inspect student performance datasets.
- Check data quality, including missing values and duplicate records.
- Validate grade values.
- Calculate descriptive statistics.
- Compare average final grades between Mathematics and Portuguese.
- Analyze study time and school absences in relation to final grades.
- Compare grades across three grading periods.
- Visualize correlations between selected numerical variables.
- Export summary statistics and charts.

## 4. Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical computing |
| Matplotlib | Charts and graphs |
| Seaborn | Statistical visualizations |
| Jupyter Notebook | Interactive analysis |
| Visual Studio Code | Development environment |

## 5. Dataset Description

The project uses two datasets:

- `student-mat.csv`: Mathematics student performance.
- `student-por.csv`: Portuguese student performance.

Important columns include:

- `studytime`: Weekly study-time category.
- `absences`: Number of school absences.
- `G1`: First-period grade.
- `G2`: Second-period grade.
- `G3`: Final grade.

Grades are recorded on a scale from 0 to 20.

## 6. Methodology

### Data Loading
The datasets are loaded from CSV files using Pandas.

### Data Quality Checks
The project checks dataset dimensions, data types, missing values, duplicate records, and grade values.

### Exploratory Data Analysis
Descriptive statistics are calculated to understand the distribution of student grades.

### Data Visualization
Histograms, bar charts, scatter plots, and a correlation heatmap are used to visualize patterns in the data.

### Results Export
Summary statistics are exported to CSV, and charts can be saved as PNG images.

## 7. Results and Discussion

The analysis examines:

- The distribution of Mathematics and Portuguese final grades.
- Differences between average final grades in the two subjects.
- Patterns between study-time categories and Mathematics grades.
- The relationship between absences and Mathematics grades.
- Average grade progression from G1 to G3.
- Correlations between selected numerical variables.

Actual numerical findings should be inserted after running the notebook and reviewing its outputs.

## 8. Limitations

- The analysis is based on the available datasets and variables.
- Correlation does not prove causation.
- Study time is recorded in categories rather than exact hours.
- The two subject datasets contain different numbers of records and should not automatically be treated as matched observations.
- Observed patterns do not establish that any single factor causes changes in academic performance.

## 9. Conclusion

This project demonstrates how Python libraries can be used to inspect, analyze, and visualize educational data.

It provides practical experience with data quality checks, descriptive statistics, exploratory data analysis, and data visualization.

The findings describe patterns in the available data and can help identify questions for further investigation.

## 10. Future Improvements

Possible extensions include:

- Building an interactive dashboard.
- Adding more statistical analysis.
- Exploring additional student characteristics.
- Generating a report automatically from the notebook.
- Developing a web interface for interactive exploration.