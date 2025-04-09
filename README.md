# Education Performance Analysis
An analysis of student academic performance based on demographic and behavioral factors.

# Table of Content
- Project Overview
- Dataset
- Data Inspection
- Data Cleaning
- Exploratory Data Analysis
  - Overview of the Data
  - Descriptive Statistics
  - Data Distribution
  - Check for Outliers
- Comparative Analysis
  - Exam Score vs Gender
  - Exam Score vs Region
  - Exam Score vs Socioeconomic Status
  - Attendance vs Gender
  - Attendance vs Region
  - Attendance vs Socioeconomic Status

- Correlation Analysis
  - Exam score vs Attendance

- Contributions

# Project Overview
The aim of this project is to analyze how student performance (measured by exam scores) is influenced by various demographic factors such as gender, region, and socioeconomic status, as well as behavioral metrics like attendance. The goal is to identify key factors that impact academic success and explore potential interventions.

# Dataset
The dataset includes the following columns:

- `Age`: Age of student
- `Gender`: Student's gender
- `Region`: Student’s region of origin
- `Socioeconomic_Status`: Socioeconomic class of the student
- `Attendance (%)`: Percentage of days the student was present
- `Exam_Score`: Student's score in final exam

# Data Inspection
Used .info() and .head() to inspect the dataset structure, data types, and sample entries. Checked for missing values and ensured the dataset was structured properly for analysis.

# Data Cleaning
- Verified and converted column data types.
- Checked for and handled missing values.
- Ensured categorical variables were correctly encoded.
- Removed or treated outliers for accuracy in visualization and modeling.

# Exploratory Data Analysis
## 1. Overview of the Data
- Descriptive Statistics: Used .describe() and other methods to summarize mean, median, standard deviation, etc.
- Data Distribution: Visualized distributions of Age, Attendance (%), and Exam_Score using histograms and boxplots.
- Check for Outliers: Identified and visualized outliers using box plots and z-score analysis.

## 2. Comparative Analysis
- Exam Score vs Gender: Compared average exam scores between male and female students.
- Exam Score vs Region: Analyzed performance trends across different regions.
- Exam Score vs Socioeconomic Status: Investigated how exam scores vary with socioeconomic background.
- Attendance vs Gender: Explored if gender has any effect on attendance rates.
- Attendance vs Region: Checked regional patterns in attendance.
- Attendance vs Socioeconomic Status: Assessed attendance trends across different socioeconomic levels.

## 3. Correlation
- Correlation Matrix: Used a scatter plot to examine relationships between students' Attendance (%), and Exam_Score.


# Contributions
Contributions are welcome! Please feel free to open an issue or submit a pull request for improvements, suggestions, or enhancements.

