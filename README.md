# EDA of HR Dataset

## Dataset Used
Raw dataset used during analysis:  
Link to dataset: [HRDataset_v14.xlsx](https://github.com/itsadil-7890/HR-EDA/blob/main/HRDataset_v14.xlsx)

---

## Initial Setup

- Imported required Python libraries for EDA.
- Loaded the dataset and converted it into a DataFrame for analysis.
- Checked basic dataset information:
  - Number of rows and columns
  - Data types of all columns
  - Missing values (only the column "DateofTermination" had 207 null values)
    - Replaced missing values with '0' instead of dropping the column
  - Checked for duplicate values (none found)

---

## Analysis Performed

- Top 10 employees receiving the highest salaries
- Identified underperforming employees who need assistance
- Listed employees with high leave counts
- Analyzed marital status of employees
- Checked which employees are involved in special projects
- Created bar charts to compare top 10 and lowest 10 salaries
- Analyzed source of recruitment using horizontal bar charts
- Analyzed performance scores by categories: Full Meets, Exceeds, Needs Improvement, and PIP
- Performed multivariate analysis:
  - Boxplot to detect salary outliers by department
  - Relationship between Engagement Survey Score and Position
  - Marital status breakdown by gender
  - Average engagement survey score by department
- Termination analysis:
  - Total number of terminated employees
  - Terminations by department and by position
- Median salary by gender
- Analyzed reasons for employee termination
- Maximum number of absences by department
- Total absences and average engagement score for each department
- Number of terminated employees and their average satisfaction score by department
- Special projects count and average absences by gender

---

## Conclusion

This analysis provides a comprehensive overview of employee performance, satisfaction, and attrition trends in the HR dataset, which can help with better decision-making.
