## Student Performance Analysis

### Overview
This project explores a dataset of student performance records to understand what factors are associated with academic outcomes. The focus is on hypothesis-driven exploration rather than building a predictive model — the goal is to investigate relationships in the data, test assumptions, and draw evidence-based conclusions.

### Objectives
- Explore the dataset structure and assess data quality (missing values, inconsistencies, duplicate/overlapping fields)
- Formulate and test hypotheses about factors that may influence student performance — e.g. study habits, attendance, parental support, and extracurricular activities
- Use descriptive statistics and visualizations to surface patterns and relationships
- Draw conclusions grounded in the data, and note where relationships are correlational rather than causal

### Dataset
Sourced from [Kaggle — Student Performance Predictions](https://www.kaggle.com/datasets/haseebindata/student-performance-predictions). Contains 1,000 student records with attributes including attendance, study hours, previous and final grades, parental support level, gender, extracurricular activity, and online class participation.

| **Column**                    | **Description**                                                                       |
|-------------------------------|---------------------------------------------------------------------------------------|
| **Student ID**                | Unique identifier for each student                                                    |
| **Name**                      | Randomly generated student name                                                       |
| **Gender**                    | Gender of the student (Male/Female)                                                   |
| **AttendanceRate**            | Percentage of classes attended. (Some values exceed 100% for error-handling practice) |
| **StudyHoursPerWeek**         | Hours spent studying weekly. (Some values are negative for error-handling practice)   |
| **PreviousGrade**             | Grade from the previous semester (out of 100).                                        |
| **ExtracurricularActivities** | Number of extracurricular activities.                                                 |
| **ParentalSupport**           | Level of parental support (High / Medium / Low).                                      |
| **FinalGrade**                | Final grade (out of 100) — Target variable for prediction.                            |
| **Study Hours**               | Daily study hours (new column).                                                       |
| **Attendance (%)**            | Attendance percentage in numeric form (new column).                                   |
| **Online Classes Taken**      | Whether the student has attended online classes (True/False).                         |

### Approach
1. Data cleaning - resolve missing values and inconsistent/overlapping columns
2. Exploratory data analysis - distributions, correlations, group comparisons
3. Hypothesis testing - check specific claims against the data (e.g. "higher study hours is associated with higher final grades")
4. Conclusions - summarize what the data does and doesn't support