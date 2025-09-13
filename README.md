# Hiring Process Analytics – Excel Data Analysis  

## Overview  
This project uses Microsoft Excel to analyze the hiring process of a company. The goal is to extract meaningful insights from raw hiring data, focusing on gender distribution, salaries, department allocation, and position tiers. Through statistical summaries and visualizations, this project helps understand workforce composition and supports informed HR decision-making.  

---

## Objectives  

### Hiring Analysis  
- Determine the gender distribution of hires.  
- Calculate the average salary offered by the company.  
- Create salary class intervals to understand distribution.  
- Visualize the proportion of employees across different departments.  
- Represent the distribution of employees across position tiers.  

---

## Tools and Technologies  
- Microsoft Excel for data cleaning, calculations, and visualizations  
- Excel functions: `SUM`, `AVERAGE`, `COUNTIF`, `IFERROR`, and others  
- Charts and Graphs: Pie charts, bar charts, and histograms  

---

## Approach  

### Data Cleaning and Preparation  
1. Checked for missing values and applied suitable handling methods.  
2. Clubbed similar categories in relevant columns to simplify analysis.  
3. Detected and handled outliers to ensure accurate statistical calculations.  

### Analysis  
1. Counted male and female hires to evaluate gender distribution.  
2. Calculated the average salary using Excel formulas.  
3. Created class intervals to visualize salary distribution.  
4. Used pivot tables, pie charts, and bar graphs to analyze department-wise employee distribution.  
5. Created charts to represent position tiers across the organization.  

---

## Sample Excel Functions  

### Gender Distribution  
```excel
=COUNTIF(B2:B1000, "Male")   // Counts number of male hires
=COUNTIF(B2:B1000, "Female") // Counts number of female hires
